# GUÍA DE EVALUACIÓN DE FRONTEND COMPASS

## NO BIFURQUE ESTE REPOSITORIO

Bienvenido a la prueba práctica para candidatos frontend en COMPASSO.

## OBJETIVO

Nuestro objetivo con este paso del proceso de reclutamiento es conocer mejor sus habilidades técnicas.

De este modo, seleccionaremos qué desafíos le transmitiremos y cuáles tendremos que prepararle mejor para cumplirlos.

## REQUISITOS DE ENTREGA

Para usar los endpoints a continuación, deberá autenticarse, por lo que utilizará la autenticación de GITHUB:
- Guía Autenticación: [https://docs.github.com/pt/developers/apps/building-oauth-apps](https://docs.github.com/pt/developers/apps/building-oauth-apps)

Nos gustaría recibir una aplicación utilizando la api de GITHUB https://developer.github.com/v3/ consumiendo los siguientes endpoits:
- Endpoint user: https://api.github.com/users/NOMBRE_USUARIO
- Endpoint repos: https://api.github.com/users/NOMBRE_USUARIO/repos
- Endpoint starred: https://api.github.com/users/NOMBRE_USUARIO/starred

La aplicación debe contener tres componentes principales:
- El campo de búsqueda.
- Visualización de resultados.
- Dos botones para realizar un resultado determinado.

Al hacer clic en los repos y los botones con estrellas, debe mostrar una lista simple de cada endoint dichos anteriormente.

Dado un usuario en particular, debería ser posible navegar directamente a la página de detalles del usuario sin tener que volver a buscar. Ej: http://localhost:3000/NOMBRE_USUARIO

- Nos gustaría buscar por usuario.
- Nos gustaría al hacer clic en el botón repos, enumerar los repositorios del usuario buscado.
- Nos gustaría al hacer clic en el botón estrellado, enumerar los repositorios más visitados por ese usuario.

Puede usar el marco css de Bootstrap para crear componentes de interfaz de usuario (si lo prefiere, los componentes se pueden crear desde cero utilizando las prácticas recomendadas).

Debe utilizar el marco de React para desarrollar la aplicación.

Puede usar Jest para probar las solicitudes realizadas.

## STACK SE ESPERA PARA LAS PRUEBAS:

- HTML 5 (Deseable la utilización de SEO, Semãntica, Usabilidade).
- JAVASCRIPT (React.js, Performance).
- CSS 3 (Deseable la utilización de SASS, LESS, Bootstrap, Escalabilidade, Responsivo, BEM CSS).

## ESCENARIO

En la página del campo de búsqueda, debería ser posible ingresar los nombres de usuario de github, los repositorios y los más visitados por los usuarios.

## EVALUACIÓN

La evaluación se realizará de la siguiente manera:

- Analicemos y compilemos su código;
- Ejecutaremos su aplicación y realizaremos pruebas para validar el cumplimiento funcional de los puntos anteriores;
- Comprobaremos que su código es limpio, fácil de entender y de mantener;
- Durante una entrevista, podemos simular una revisión de su código, revisamos el código con usted para discutir sus decisiones de implementación, los puntos positivos y negativos;
- El balance entre lo positivo y lo negativo determinará la recomendación, desde un punto de vista técnico, o no de su contratación. (Si queda poco para llegar a una recomendación positiva, le daremos una fecha límite para corregir y devolver);


Requisitos obligatorios:

- Verifique las mejores prácticas enfocadas en CSS 3 y la Metodología BEM CSS;
- Verifique las buenas prácticas para React;
- Verifique las buenas prácticas para HTML 5;

## CONSEJOS:

- Tenga en cuenta que su evaluador ejecutará el código antes de hablar con usted;
- Trate de hacer una entrega simple pero consistente, utilizando la experiencia y los conocimientos adquiridos durante su carrera;
- No se preocupe por entregar algo extremadamente completo o exagerado, no usaremos este código en producción;

Todo será evaluado, ¡haz lo mejor que pueda!
