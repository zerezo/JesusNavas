Enunciado
Hacer un proyecto Xcode que implemente una app iOS usando SwiftUI y que muestre y permita jugar con los quizzes contenidos en el fichero quizzes.json. Este fichero está disponible en el moodle de la asignatura.

La pantalla principal de la app debe mostrar una view de tipo List con todos los quizzes leidos de quizzes.json. Cada elemento de esta lista debe mostrar:

La pregunta de un quiz.
Su imagen adjunta.
Una estrella iluminada o apagada dependiendo de si el quiz está marcado como favorito o no.
El nombre y la foto del autor del quiz.
La lista de quizzes debe usarse dentro de un NavigationStack. Use NavigationLinks, para que al pulsar sobre un quiz de la lista, se presente otra pantalla donde se pueda jugar a adivinar la respuesta del quiz seleccionado.

La pantalla de jugar a adivinar un quiz debe:

Mostrar toda la información sobre el quiz seleccionado, excepto su respuesta correcta.
Contener un TextField donde el jugador escribirá la respuesta del quiz, y un botón para comprobar si la respuesta introducida es correcta. Después de pulsar en el botón de comprobación, se debe presentar una alerta indicando si la respuesta introducida es correcta o incorrecta.
Mostrar en la barra de navegación un título descriptivo y un botón para volver a la página inicial de la app.
La pantalla principal que muesta la lista de todos los quizzes, debe mostrar en la barra de navegación un contador que indique cuántos quizzes diferentes se han acertado hasta el momento. Esto puede implementarse manteniendo un array con los id's de los quizzes acertados. La puntuación acumulada del usuario será simplemente el tamaño de ese array.

Añadir una pantalla inicial de lanzamiento y los iconos de escritorio, configuración, etc...

Todas las vistas deben adaptar su contenido para que se visualice correctamente para cualquier tipo de terminal y orientación.

El alumno tiene disponible en el moodle varios ficheros que debe utilizar para hacer esta práctica.

quizzes.json - Es un fichero JSON con los quizzes que hay que usar.
QuizzesModel.swift - Fichero Swift que implementa un modelo que contiene los quizzes cargados del fichero quizzes.json.
QuizItem.swift - Fichero Swift que define la struct que representa cada quiz.
Vista Quizzes Vista Quizzes Vista Quizzes Respuesta erronea Respuesta correcta Vista Horizontal

Evaluación
Esta práctica debe hacerse en grupos.
La realización de esta práctica es obligatoria.
La entrega de la práctica se hace subiendo a moodle un zip con los fuentes.
Solo uno de los miembros del grupo debe subir la práctica.
Incluir en la raíz del ZIP un fichero 00datos.txt con el nombre de todos miembros del grupo.
Si no se entrega en plazo se calificará con 0 puntos.
Se recomienda subir la práctica a moodle con bastante antelación para evitar problemas de última hora que impidan su entrega.
Puntuación:
La práctica se valorará con 0 puntos si se entrega un ZIP que no contenga todos los ficheros de la prácticas.
Se recomienda a los alumnos que prueben el ZIP en un ordenador distinto al usado para desarrollar la práctica. La practica debe compilar y funcionar en ese ordenador de pruebas.
Un error muy común es entregar un proyecto con enlaces a ficheros que estaban localizados en el directorio de descargas, y que por tanto no se han incluido en el fichero zip creado con el directorio del proyecto.
Si la práctica no compila, se valorará con 0 puntos.
Si la práctica funciona correctamente y es bonita se valorará hasta con 2 puntos.
Mostrar el listado de Quizzes con foto y pregunta, y navegar a la vista de jugar - 0.5 puntos
Comprobar respuesta y alert informativo - 0.5 puntos
Gestión de la puntuación - 0.5 puntos
Título en la barra de navegación, tiene imagen de lanzamiento e iconos, y es muy bonita - 0.5 puntos
