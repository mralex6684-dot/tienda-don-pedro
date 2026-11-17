markdown
# Tienda Don Pedro

Sistema de control de **inventario**, **precios**, **fiado** y **domicilios** para la tienda de barrio de *Don Pedro*.

## ¿Qué vende Don Pedro?

- Panadería y lácteos (pan tajado, leche, huevos)
- Granos y abarrotes (arroz, frijol, aceite)
- Productos de aseo y consumo diario

## Estructura del proyecto

| Archivo | Descripción |
|---|---|
| `datos/productos.txt` | Catálogo de productos y precios actualizados |
| `datos/fiado.txt` | Registro de clientes con cuentas pendientes |
| `datos/descuentos.txt` | Descuentos aplicados a clientes frecuentes |
| `datos/domicilios.txt` | Tarifas de envío por barrio |

## Cambios realizados

- Creación de ramas independientes para nuevas funciones (`fiado`, `descuentos` y `domicilios`)
- Resolución de conflictos de precios en `datos/productos.txt`
- Documentación del proyecto en formato Markdown