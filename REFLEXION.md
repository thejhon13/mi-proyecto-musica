# Reflexión — Playground de Música Generativa

## 1. ¿Qué es un iframe y qué ventajas y desventajas tiene frente a integrar el código de Strudel directamente en tu página?

Un iframe es un elemento HTML que permite incrustar contenido externo dentro de una página web. En este proyecto se utilizó para integrar el editor de Strudel directamente desde su sitio oficial.

La principal ventaja es que facilita la integración sin necesidad de instalar librerías o configurar el entorno musical manualmente. Además, permite reutilizar una herramienta ya funcional y estable.

Como desventaja, el iframe depende de una página externa. Si Strudel deja de funcionar o cambia su estructura, el proyecto puede verse afectado. También existe menos control sobre la personalización interna del editor.

---

## 2. El patrón de Strudel es texto plano. ¿Cómo lo guardarías en una base de datos si quisieras que los usuarios creen y guarden sus propios patrones?

Los patrones de Strudel podrían almacenarse como texto en una base de datos. Cada patrón tendría atributos como:

- nombre del patrón,
- contenido del código,
- usuario creador,
- fecha de creación.

Por ejemplo, en una base de datos SQL se podría usar una tabla llamada `patrones` con un campo tipo TEXT para guardar el código musical.

---

## 3. Este proyecto es educativo. ¿Qué cambiarías en el diseño si el público objetivo fueran niños de primaria en lugar de estudiantes universitarios?

Si el proyecto estuviera dirigido a niños de primaria, utilizaría colores más llamativos, botones más grandes y una interfaz más visual e interactiva.

También agregaría ilustraciones, sonidos más simples y explicaciones cortas con ejemplos animados para facilitar el aprendizaje musical mediante juegos y exploración visual.