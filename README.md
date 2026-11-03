# Chingo Café Pro

Aplicación web demostrativa para administrar un pequeño negocio de café en grano y molido.

## Publicar en GitHub Pages
1. Abre Settings → Pages en este repositorio.
2. En Build and deployment selecciona **Deploy from a branch**.
3. Branch: **main**; folder: **/(root)**; pulsa Save.
4. Espera a que GitHub Pages termine el despliegue.
5. La URL será https://zenon2805.github.io/ChingoCafe/

## Módulos
- Resumen de ventas y pedidos.
- Catálogo: alta, edición y eliminación de productos.
- Inventario: entradas y salidas con validación.
- Pedidos: registro, consulta y cambio de estado.
- Clientes: alta y consulta.
- Simulador de atención tipo WhatsApp: menú, agregar, carrito y confirmar.
- Reportes: ventas, ticket promedio y exportación CSV.
- Configuración: datos comerciales y respaldo JSON.
- Pruebas funcionales desde el módulo Pruebas.

## Datos y limitaciones de esta versión
Esta versión es una **demo web estática**. Guarda información en localStorage del navegador. Los datos no se sincronizan entre equipos, navegadores ni usuarios; no usar como sistema de caja productivo ni almacenar datos sensibles. Los datos iniciales son de ejemplo.

El simulador de WhatsApp no envía mensajes. La integración real necesita un backend seguro, una base de datos persistente, una cuenta Meta Business, WhatsApp Cloud API, token de acceso y webhook HTTPS. No publiques tokens ni contraseñas en este repositorio.

## Pruebas
Abre el módulo **Pruebas** y ejecuta el conjunto de comprobaciones. Son verificaciones de consistencia de datos, cálculos, importación/exportación y estructura. No sustituyen pruebas de seguridad, concurrencia o integración real con Meta.
