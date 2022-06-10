#
# **Desafío WordPress**

En este desafío, creará un plugin para WordPress que añada el shortcode [todolist], el cuál muestra una lista de tareas.

![alt text](https://github.com/newcombin/devskillsWP/blob/main/template.png "Diseño web")

\* El diseño es sólo ilustrativo, puedes personalizarlo a gusto.

## **Contexto**

Se desea mostrar una lista de tareas dinámica en la que se pueda agregar, eliminar o marcar como completada diferentes tareas.

Pueden existir múltiples tareas con el mismo nombre.

## **Requisitos**

**Estructura:**

- Debe tener un título &quot;To Do List&quot;
- Debe mostrar un input y un botón para añadir tareas
- Las nuevas tareas se deben agregar al principio de la lista

**Tarea:**

- Un tarea consiste en un checkbox, un título y un botón para eliminarla
- Cada tarea se puede marcar como completada o desmarcar las veces que se quiera
- Cada vez que una tarea se marca como completada el texto debe tacharse
- Cuando se elimina una tarea esta desaparece de la lista

**Técnicos:**

- Puede crear un plugin desde cero o utilizar un boilerplate si lo prefiere
- Debe crear un Custom Post Type que almacene estas tareas y permita administrarlas desde el área administrativa de WordPress
- Las tareas son globales y no distinguen entre usuarios
- Debe utilizar ajax para agregar, eliminar o marcar como completadas las tareas, de forma que no sea necesario recargar la página
- Al cargar la página las tareas completadas deben estar tachadas y el checkbox marcado
- Para las funcionalidades Javascript puede usar jQuery, aunque se prefiere Vanilla JavaScript

**Entrega**

- Crear un archivo README.md para indicar como se debe utilizar el plugin
- Subir a un repositorio git con privilegios públicos de lectura y compartir el link
