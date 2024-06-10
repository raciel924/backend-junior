# Prueba Técnica: Backend Junior

## Objetivo

Crear un proyecto en Laravel para la realización de endpoints autenticados sobre el siguiente sistema.

## Requisitos

1. **Login y Registro**
   - Roles: Admin, Cliente

2. **Sistema Admin**
   - Alta de libros
   - Alta de autores de libros
   - Alta de categorías
   - Alta de editoriales
   - Generación de ticket (préstamo de libro a cliente)

3. **Búsqueda de Libros**
   - Por título
   - Por categoría
   - Por editorial

4. **Base de Datos**
    https://drive.google.com/file/d/10tIspvpLl1uDcv8vwYlNkth9AcIRZkC3/view

5. **Endpoints**
   - Crear endpoints para cada uno de los casos anteriores.

## Desarrollo

### Pasos a seguir

1. **Inicialización del Proyecto**
   - Crear un nuevo proyecto en Laravel.
   - Configurar la base de datos en el archivo `.env`.

2. **Autenticación**
   - Implementar Login y Registro utilizando Middleware o  Laravel Sanctum.
   - Configurar roles (Admin, Cliente).

3. **Migraciones, Seeders y Factories**
   - Crear migraciones para las tablas necesarias (libros, autores, categorías, editoriales, usuarios, tickets).
   - Crear seeders para poblar la base de datos con datos de ejemplo.
   - Opcional: Crear factories para generar datos falsos.

4. **Modelos**
   - Crear los modelos correspondientes (Book, Author, Category, Publisher, User, Ticket).

5. **Controladores**
   - Crear controladores para manejar las operaciones CRUD de libros, autores, categorías, editoriales y tickets.
   - Crear controladores para las operaciones de búsqueda.

6. **Rutas**
   - Definir las rutas necesarias en `routes/api.php`.

### Entregables

- Código fuente del proyecto en un repositorio Git.
- URL del repositorio para acceder al proyecto.

### Duración

- Tiempo estimado para completar la prueba: **24 horas**

## Entrega

- Enviar la URL del repositorio donde se encuentra el proyecto completado.

---

### Nota

Asegúrate de seguir las mejores prácticas de desarrollo y estructuración de proyectos en Laravel. Buena suerte con la prueba técnica.
