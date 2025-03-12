# Legibilidad
| Asignatura | Enlace al repo | Reto|
|------------|---------------|------|
| Progra 1  | [Repositorio](https://github.com/rubensetien/prg1-22-23) | [Reto](https://github.com/rubensetien/prg1-22-23/blob/main/Whac-A-MoleRub%C3%A9nSeti%C3%A9n.java)
| Progra 2  | [Repositorio]() | [Reto]()|
| EDA 1     | [Repositorio]() | [Reto]()|
| EDA 2     | [Repositorio]() | [Reto]()|

## 1. Nombres no descriptivos o ambiguos
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto WhacAMole| [WhacAMole.java](https://github.com/rubensetien/prg1-22-23/blob/main/Whac-A-MoleRub%C3%A9nSeti%C3%A9n.java)| [6]()| `subir` |  `metrosSubidos` |
| EX003Inheritance| [v]()| `userAdmin`| `isAdmin`|
| Carrefour| [GenerarCliente]()||Nombre de la clase| `GeneradorCliente.java`|
|Biblioteca| [Biblioteca.java]()|`Gestor manager`|`gestorDocumentos`|

## 2. Uso de Nombres Inconsistentes

| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [v]()| [5]() y [26]()| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [v]()| [5-7]()|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [v]()|[16]()|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|
|Biblioteca| [v]()| [112]()| Mal escrito `eleminarTodosLosDocumentos`| `eliminarTodosLosDocumentos`|

## 3. Problemas de Sintaxis 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java]()| [47]() | `for (int j = 0; j <= dimension; j = j + 1)`| `for (int j = 0; j <= dimension; j = j + 1){}`|
|EX003Inheritance| [Admin.java]()| [4]() y [9]()| `isAdmin`| La variable booleana nombrarla `adminRole`|
|Biblioteca|[GestorAutores.java]()|[33]()|`String nuevoNombre = System.console().readLine();`|`Scanner sc = new Scanner(System.in);` `String nuevoNombre = sc.nextLine();`|

## 4. Métodos Repetitivos 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [v]()| [5]() y [26]()| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [v]()| [5-7]()|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [v]()|[16]()|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|
|Biblioteca| [v]()| [112]()| Mal escrito `eleminarTodosLosDocumentos`| `eliminarTodosLosDocumentos`|

## 2. Uso de Nombres Inconsistentes

| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [v]()| [5]() y [26]()| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [v]()| [5-7]()|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [v]()|[16]()|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|
|Biblioteca| [v]()| [112]()| Mal escrito `eleminarTodosLosDocumentos`| `eliminarTodosLosDocumentos`|

## 5. Código no DRY (Don't Repeat Yourself)
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [v]()| [5]() y [26]()| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [v]()| [5-7]()|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [v]()|[16]()|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|
|Biblioteca| [v]()| [112]()| Mal escrito `eleminarTodosLosDocumentos`| `eliminarTodosLosDocumentos`|

## 6. Falta de encapsulación 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [v]()| [5]() y [26]()| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [v]()| [5-7]()|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [v]()|[16]()|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|
|Biblioteca| [v]()| [112]()| Mal escrito `eleminarTodosLosDocumentos`| `eliminarTodosLosDocumentos`|


