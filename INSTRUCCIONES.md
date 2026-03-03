# Instrucciones para Agregar Productos y Personalizar el Catálogo

## Introducción
Este documento proporciona instrucciones detalladas sobre cómo agregar productos, personalizar el catálogo y implementar nuevas características en el repositorio.

## Agregar Productos
1. **Acceder al archivo de productos:** Ve a la carpeta `productos/`.
2. **Agregar un nuevo archivo:** Crea un nuevo archivo para el producto en formato `.md` o `.json`, incluyendo:
   - Nombre del producto
   - Descripción
   - Precio
   - Imágenes ( URLs)
   - Categoría
3. **Ejemplo de producto:**
   ```json
   {
       "nombre": "Nombre del Producto",
       "descripcion": "Descripción del producto",
       "precio": 100,
       "imagen": "url/a/la/imagen",
       "categoria": "categoria"
   }
   ```
4. **Commit de cambios:** Asegúrate de hacer commit de tus cambios y subirlos a la rama principal.

## Personalizar el Catálogo
1. **Modificar el archivo de configuración:** Accede al archivo `config.json`. Modifica los parámetros según sea necesario.
2. **Agregar nuevas categorías:** Para agregar nuevas categorías, simplemente añade un bloque similar al formato anterior en el archivo de configuración.

## Implementar Nuevas Características
1. **Definir la nueva característica:** Antes de implementar, asegúrate de tener una clara comprensión de cómo debe funcionar la característica.
2. **Crear una nueva rama:** Crea una nueva rama basada en `main` usando el comando `git checkout -b nombre-de-la-rama`.
3. **Codificación y pruebas:** Una vez que implementes la característica, realiza pruebas exhaustivas antes de hacer commit.
4. **Merge a main:** Después de probar, haz un pull request para merger tus cambios a la rama principal.

## Conclusiones
Asegúrate de seguir estas instrucciones para mantener la coherencia y el orden en nuestro catálogo de productos. Para cualquier duda, contacta al administrador del repositorio.