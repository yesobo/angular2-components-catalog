# Catálogo de componenentes Angular 2

Catálogo de componentes Angular 2.

# Requisitos

- Posibilidad de agrupación de componentes.
- Buscador de componentes.
- Cada elemento tendrá su página de demo.
- Cada elemento tendrá su documentación.
- Los elmentos estarán empaquetados con un prefijo común.


## Nomenclatura empaquetados

@companyname-ng2/select
ejemplo: https://www.npmjs.com/package/@angular2-material/button

## nomenclatura componentes

```
<cc-ng2-select></cc-ng2-select>
```

Where cc- is the company code.

## Demo componente.
- Cada Elemento tendrá su demo/index.html con sus ejemplos

  ej: https://github.com/PolymerElements/paper-badge/blob/master/demo/index.html

  Cada ejemplo se representará con un componente <demo-snippet> cuyo contenido se visualizará y se renderizará para evitar escribir dos veces el mismo código.

## Documentación componente.

La documentación de un componente estará contenida en:

- En su fichero `package.json`
- En su fichero `README.md`
-

## Diseño catálogo

### Sidebar (app-sidebar)

### Main (header + main)

## Carga de un componente
El router carga el componente al hacer click en el enlace elements/componente-name

## Categorías
Listadas en catalog.json de la forma:

```
{
  "name":"platinum-elements",
  "title":"Platinum Elements",
  "color":"#cfd8dc",
  "symbol":"Pt",
  "tagline":"Offline, push, and more"
},
{
  "name":"molecules",
  "title":"Molecules",
  "color":"#ffab91",
  "symbol":"Mo",
  "tagline": "Wrappers for third-party libraries"
}
```
