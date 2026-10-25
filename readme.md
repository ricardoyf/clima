# clima

Mapa mental, tabla comparativa, apuntes ilustrados, juego y tarjetas de repaso sobre los climas, en gallego, castellano e inglés.

**Abrir:** https://ricardoyf.github.io/clima/

## Primero clasificar

La primera pestaña, **Mapa mental**, empieza con tres grupos. Al tocarlos aparecen solo los nombres de sus climas:

- **Templados:** Mediterráneo, Oceánico y Continental.
- **Cálidos:** Ecuatorial, Tropical seco y Desértico.
- **Fríos:** Polar y Altas montañas.

Las llaves permiten desplegar cada grupo. Al tocar un clima se muestran las palabras clave; los controles permiten seguir con una frase, una explicación y una relación con otras ideas. La pertenencia al grupo sigue visible.

**Ver clasificación completa** abre todos los grupos y cierra las explicaciones. **Cerrar todo** recoge el esquema. **Imprimir mapa** incluye los tres grupos y los ocho nombres, aunque estén plegados en pantalla.

Los tres grupos de climas se distinguen de las cinco zonas climáticas, que se explican en la ficha del ecuador.

## Comparar los mismos aspectos

La pestaña **Tabla** organiza los ocho climas en filas y sus **temperaturas, precipitaciones y vegetación o paisaje** en columnas. Conserva los grupos templados, cálidos y fríos y permite estudiar con pocas palabras.

**Completar** ofrece cuatro actividades:

1. **Columnas:** identificar los tres encabezados.
2. **Climas:** identificar los ocho nombres de fila.
3. **Datos:** completar un dato de cada clima.
4. **Mezcla:** tres encabezados, cuatro nombres y cuatro datos de las otras filas: once huecos, con pistas suficientes.

Las filas se barajan dentro de sus grupos y las columnas cambian de posición junto con sus datos. El orden permanece al cambiar de idioma. Las respuestas equivalentes, como «Calor», comparten una opción válida.

La práctica permite comprobar y corregir; el examen fija las respuestas al terminar y muestra la corrección. El progreso de estas actividades se registra por separado.

La vegetación de alta montaña **no se especifica en esta lección**: aparece como «No se indica» y nunca se evalúa como un hueco. Eso no significa que no exista vegetación.

## Apuntes y juego

Incluye 15 fichas ilustradas y 75 ejercicios activos, organizados en cuatro escalones:

1. Palabras clave: reconocer ideas.
2. Frases: construir la frase estudiada.
3. Explicación: expresar las ideas con palabras propias.
4. Relación: comparar y explicar causas.

El juego permite rondas de 10 o 15 preguntas. Los dos primeros escalones tienen práctica con corrección inmediata y examen con corrección al final. Los escalones 3 y 4 usan respuestas orientativas y una autoevaluación por ideas, identificada como tal.

Las tres pestañas de idioma mantienen el mismo contenido y los mismos ejercicios. Cambiar de idioma conserva la sesión, las respuestas y el orden de opciones.

## Tarjetas de repaso tipo Anki

La pestaña **Tarjetas** añade **28 tarjetas** en gallego, castellano e inglés. Primero aparece una pista; el niño piensa o dice la respuesta y pulsa **Mostrar respuesta**. Después valora si la recordaba antes de mirar.

Ejemplos: **taiga → continental**, **sabana → tropical seco** y **lluvias concentradas en una estación → tropical seco**. También hay preguntas sobre los demás climas, sus grupos, instrumentos y factores del clima.

**Repaso de hoy** presenta primero las tarjetas pendientes y después las nuevas, en rondas de 10 o todas. La programación es sencilla y propia, no el algoritmo de Anki:

- **Otra vez:** vuelve tras otras dos tarjetas —o al final si quedan menos—, hasta tres apariciones por ronda. Si sigue olvidada, queda pendiente para hoy. Reinicia el intervalo.
- **Difícil:** un día; reinicia al primer paso.
- **Bien:** tres días la primera vez y después el siguiente paso.
- **Fácil:** siete días la primera vez y después dos pasos más.
- Escala: **1, 3, 7, 14, 30, 60, 120 y 180 días**, con un máximo de 180.

**Práctica libre** permite repasar cualquier tarjeta sin alterar las fechas ni las estadísticas del repaso programado. Pausar, recargar o cambiar de idioma conserva la ronda. Las tarjetas también se incluyen en la copia de progreso. Las calificaciones son autoevaluaciones; la página no escucha ni corrige una respuesta oral.

**Exportar a Anki** descarga un texto UTF-8 de dos columnas —anverso y reverso—, con cabeceras de importación. En Anki, elige **Importar**, selecciona el archivo y utiliza un tipo de nota **Básico**, asignando la primera columna al anverso y la segunda al reverso. Se exportan los textos del idioma seleccionado; el calendario del HTML no se transfiere y Anki programa sus propios repasos. No es un archivo `.apkg`. Consulta la [importación oficial de textos](https://docs.ankiweb.net/manual/importing/text-files).

**Imprimir tarjetas** crea 28 parejas de pista y respuesta para plegar por la línea discontinua o recortar.

## Crear nuevos temas

La página [crear apuntes](https://ricardoyf.github.io/clima/crear-apuntes/) prepara el prompt completo a partir de unos campos y ofrece ejemplos interactivos de climas, inglés y francés. Copia el prompt y adjunta las fotos en la conversación con tu agente.

El [prompt completo](crear-apuntes/prompt.md) también se puede leer sin ejecutar JavaScript. La carpeta `crear-apuntes/` contiene una web autónoma preparada para publicarse en un repositorio propio. Actualmente se publica como una subpágina de `clima`; no presupone que exista un repositorio independiente.

## Impresión

- **Imprimir mapa:** únicamente la clasificación completa con llaves, grupos y nombres.
- **Imprimir apuntes:** clasificación inicial y las 15 fichas del escalón elegido, agrupadas bajo sus categorías escritas.

- **Imprimir tabla:** los ocho climas y sus características completas.
- **Examen + soluciones:** tabla con los huecos de la actividad elegida y solucionario en una página aparte.
- **Imprimir tarjetas:** 28 parejas de pista y respuesta para plegar o recortar.

Todas estas opciones usan el idioma seleccionado. Los conceptos y factores se imprimen en su propio apartado, fuera de los grupos de tipos de clima.

## Guardarlo para otros cursos

Abre `index.html` en un navegador. El archivo incluye CSS, JavaScript, textos, dibujos y ejercicios, y funciona sin conexión.

En las opciones al final de la página, **Descargar HTML** guarda una copia llamada `clima.html`. El progreso se guarda por separado en el navegador cuando este lo permite. **Descargar progreso** y **Restaurar progreso** permiten trasladarlo a otro dispositivo o curso.

La actualización mantiene el formato anterior de las copias del progreso.

## Publicación

GitHub Pages publica la raíz de la rama `main`. `.nojekyll` permite servir el HTML directamente.

## Prompt para preparar otras asignaturas

Copia el texto siguiente y adjunta las fotos de la nueva lección.

```text
Convierte las fotos de esta lección en unos apuntes interactivos con juego y examen dentro de un único archivo HTML. Deben servir para estudiar ahora y recuperarlos en cursos posteriores.

Asignatura y tema: [INDICAR]
Curso o edad: [INDICAR]
Repositorio o página existente, si corresponde: [INDICAR]

PRIORIDAD ABSOLUTA: PRIMERO CLASIFICAR; DESPUÉS PROFUNDIZAR

1. Fidelidad al material

Lee todas las fotos antes de diseñar. Conserva conceptos, clasificaciones, relaciones, ejemplos y vocabulario esencial. No inventes datos ni omitas información necesaria para el examen. Si algo no se lee, señala el fragmento y pide una imagen mejor; avanza con las partes legibles.

Distingue categorías, subcategorías, propiedades y ejemplos. No los pongas al mismo nivel. Si el tema se organiza por partes, etapas, procesos o relaciones, respeta esa estructura. No fuerces una clasificación artificial. Si hay un HTML anterior, conserva su contenido correcto y el progreso guardado.

2. Primera pestaña y pantalla inicial: «Mapa mental»

Antes de las palabras clave, el niño debe ver dónde pertenece cada cosa.

Crea un esquema con llaves desplegables. Al principio muestra solo el tema y sus grandes grupos. Al tocar un grupo, aparecen únicamente los nombres de sus elementos. Sin definiciones, párrafos, pistas ni dibujos que recarguen esta vista.

Ejemplo para la lección de climas:
— Climas templados: Mediterráneo, Oceánico, Continental.
— Climas cálidos: Ecuatorial, Tropical seco, Desértico.
— Climas fríos: Polar, Altas montañas.

«Tropical seco» es un solo tipo. Adapta los grupos y el número de elementos al tema real; no copies los del ejemplo a otras asignaturas.

Incluye «Ver clasificación completa», «Cerrar todo» e «Imprimir mapa». Ver la clasificación completa abre todos los grupos y muestra solo nombres. Cerrar un grupo elimina sus detalles abiertos, para que vuelva a mostrar solo nombres al reabrirse.

Al tocar un concepto, permite profundizar progresivamente:
nombre → palabras clave → frase → explicación → relación.

Mantén visible su pertenencia al grupo. Permite retroceder y abrir la ficha correspondiente.

3. Detecta los patrones y conviértelos en ejercicios

Además de clasificar, identifica por iniciativa propia qué aspectos se repiten al describir los elementos: propiedades, funciones, causas, consecuencias, etapas, ejemplos, semejanzas o diferencias.

Si varios elementos comparten las mismas características de descripción, crea una tabla comparativa. Las filas serán los elementos y las columnas los aspectos comunes. Conserva las categorías y usa pocas palabras por celda. Por ejemplo: climas en las filas; temperaturas, precipitaciones y vegetación en las columnas. Confirma el patrón en el material y no impongas esas columnas a otros temas.

Cuando la fuente no dé un dato, escribe «No se indica en la lección». No lo inventes ni lo conviertas en una pregunta.

Incluye una pestaña de tabla con estudio y cuatro actividades progresivas: completar encabezados de columnas, nombres de filas, algunos datos y una mezcla. Antes de generar huecos, conserva pistas suficientes; una fila cuyo nombre esté oculto debe mantener los datos necesarios para reconocerla. Acepta respuestas equivalentes, sin penalizar etiquetas idénticas por proceder de filas distintas.

Baraja filas dentro de sus grupos y columnas junto con sus datos. Mantén el orden y las respuestas al cambiar de idioma. No reveles respuestas en placeholders o etiquetas accesibles.

Ofrece práctica con reintentos, examen con corrección final y un examen imprimible con solucionario en otra página. Guarda el progreso de las tablas por separado del juego de fichas. Explica qué patrón has detectado y para qué sirve.

4. Apuntes en cuatro escalones

La clasificación es la entrada a estos cuatro escalones:

1.º Palabras: las mínimas palabras clave necesarias, normalmente entre tres y seis.
2.º Frase: una oración breve que conecte esas palabras.
3.º Explicación: unas pocas frases con las ideas esenciales.
4.º Relación: comparar, justificar, aplicar o conectar conceptos.

No elimines distinciones esenciales para reducir palabras. Cada nivel debe añadir comprensión, sin convertir un resumen breve en una afirmación falsa.

Usa dibujos sencillos cuando ayuden a entender. Una idea por ficha, letras claras, botones cómodos y poco ruido visual.

5. Juego y examen

Relaciona cada ejercicio con lo estudiado en su nivel:
— Palabras: reconocer, clasificar y recordar.
— Frase: ordenar o completar una frase breve.
— Explicación: expresar varias ideas.
— Relación: comparar, explicar causas o aplicar lo aprendido.

Incluye rondas cortas y una opción de repaso del tema completo, con cobertura de todos los conceptos. En práctica, muestra la corrección tras cada respuesta; en examen, al terminar. Ofrece explicación breve, repaso de errores y progreso, sin una cuenta atrás obligatoria.

Corrige automáticamente las preguntas cerradas. Para respuestas abiertas, muestra una respuesta orientativa y una lista de ideas para autoevaluarse. Identifica claramente esta autoevaluación. No simules comprender respuestas libres mediante coincidencias de palabras.

6. Tarjetas de repaso tipo Anki

Añade una pestaña «Tarjetas» para recordar una respuesta antes de verla. Genera las tarjetas a partir de la lección: palabras asociadas, conceptos, características distintivas, pertenencia a grupos y relaciones importantes. Una tarjeta debe evaluar una sola idea, con un anverso breve y un reverso que incluya la respuesta y, cuando ayude, una explicación de una frase.

Ejemplos de climas:
— «Taiga: ¿qué clima?» → «Continental».
— «Sabana: ¿qué clima?» → «Tropical seco».
— «¿En qué clima cálido se concentran las lluvias en una estación?» → «Tropical seco».

Evita pistas ambiguas. «Llueve mucho» puede corresponder a varios climas: añade información suficiente o acepta todas las respuestas válidas. No inviertas automáticamente las tarjetas; comprueba que la pregunta inversa también tenga una respuesta clara. No reveles respuestas con dibujos, categorías, colores, etiquetas accesibles o pistas involuntarias en el anverso.

Funcionamiento:
— Mostrar una tarjeta cada vez, con la respuesta oculta.
— Invitar a pensar o responder en voz alta, sin exigir micrófono.
— Ofrecer «Mostrar respuesta».
— Solo entonces permitir autoevaluarse: «Otra vez», «Difícil», «Bien» o «Fácil».
— Repetir las tarjetas olvidadas durante la sesión y programar repasos posteriores mediante intervalos sencillos.
— Mostrar el siguiente intervalo y guardar el progreso por tarjeta.

Explica la regla de intervalos utilizada, incluidos los reinicios tras un olvido y el máximo de repeticiones. Identifica la actividad como repaso tipo Anki y la valoración como autoevaluación; no afirmes que es el algoritmo oficial de Anki ni que se ha corregido automáticamente una respuesta oral. Cada control debe cambiar realmente la programación. No prometas avisos si la página solo muestra los repasos al abrirse.

Incluye rondas breves, repaso de pendientes antes de tarjetas nuevas y práctica libre. La práctica libre no modifica fechas ni estadísticas del repaso programado. Conserva la tarjeta, la cola, el reverso y el progreso al cambiar de idioma, pausar o recargar. Evita calificar dos tarjetas por una doble pulsación. Una ronda terminada puede dejar tarjetas pendientes; no lo presentes como «todo aprendido».

Guarda fechas de calendario local válidas; comprueba cambios de mes y año. Incluye tarjetas y sesiones en la copia de progreso. Al importar, conserva la revisión más reciente: una fecha futura más lejana no equivale a mayor aprendizaje y no debe borrar un olvido reciente. Acepta las copias antiguas que no tengan tarjetas.

Ofrece impresión y, si incluyes «Exportar a Anki», genera un archivo real de texto UTF-8 con dos campos, anverso y reverso, compatible con la importación de Anki. Explica cómo importarlo; no lo llames archivo .apkg si no lo es. El calendario del HTML y el de Anki son independientes.

Para temas de idiomas, separa el idioma de la interfaz de los idiomas de pregunta y respuesta. Crea intencionadamente comprensión y producción; cada dirección y lengua de estudio tiene su propio ID y su propio progreso. Cambiar la interfaz no debe traducir la palabra extranjera que se está aprendiendo.

Ejemplos:
— Castellano → inglés: «Hace frío» → «It's cold»; también es válida «It is cold».
— Inglés → castellano: «It's cold» → «Hace frío».
— Castellano → francés: «la casa» → «la maison».
— Francés → castellano: «la maison» → «la casa».
— Una frase más: «La casa es pequeña» → «La maison est petite».

Incluye artículos y género cuando sean relevantes, especialmente en francés, y frases breves con contexto. Acepta traducciones alternativas correctas. No elimines contexto para conseguir respuestas artificialmente únicas.

7. Tres idiomas completos

Incluye Galego, Castellano y English, con gallego inicial salvo que yo indique otro idioma.

Traduce naturalmente todo: clasificación, apuntes, dibujos con texto, botones, preguntas, opciones, explicaciones, rúbricas, resultados e impresión. Mantén las mismas ideas, ejercicios y dificultad.

Cambiar de idioma conserva el mapa abierto, el ejercicio, las respuestas, el orden de opciones y el progreso. Usa identificadores comunes. Las frases ordenables deben resultar naturales y coincidir exactamente con la frase estudiada en cada idioma.

8. Impresión

Ofrece estas salidas distintas:
— Mapa mental: clasificación completa desplegada, solo categorías y nombres, con sus llaves.
— Apuntes: clasificación al principio y todas las fichas del nivel elegido, agrupadas bajo sus categorías escritas.
— Tabla comparativa: todos los elementos y sus características.
— Examen de tabla: los huecos de la actividad seleccionada, con solucionario en otra página.
— Tarjetas: pistas y respuestas, para recortar o plegar y repasar sin pantalla.

La impresión usa el idioma seleccionado. Los apartados plegados no desaparecen del papel. Conserva la jerarquía y la categoría de cada ficha; el color nunca debe ser la única pista. No confundas los apuntes de palabras clave con el contenido de los niveles superiores.

Diseña para A4 y blanco y negro. Evita cortar fichas o separar títulos de su contenido. Si incluyes un examen imprimible, coloca el solucionario aparte.

9. Conservación y accesibilidad

Entrega un HTML autónomo con CSS, JavaScript, datos y dibujos incorporados, sin dependencias externas necesarias para funcionar. Debe abrirse sin conexión.

Incluye descarga del HTML, progreso local y exportación e importación de una copia del progreso. Valida las importaciones. Conserva el progreso anterior al actualizar. Centraliza contenidos y traducciones para ampliarlo otros años.

Adapta el diseño a móvil y ordenador, con teclado, botones accesibles, buen contraste y textos legibles.

10. Revisión y entrega

Prueba desplegables, niveles, ejercicios, traducciones, impresión y conservación del progreso. En tarjetas, verifica el ocultamiento de respuestas, los intervalos, las repeticiones, la práctica libre, los cambios de idioma, la recarga y las copias de progreso. Comprueba que todas las categorías y conceptos de las fotos estén representados y que cada pregunta pueda responderse con lo estudiado.

Entrega el HTML completo descargable y explica brevemente cómo usarlo. Si pido actualizar GitHub, publica la versión, verifica su despliegue y dame el enlace. Usa nombres nuevos y enlaces en minúsculas.

Distingue lo que has verificado en el código de lo que has comprobado visualmente. No afirmes haber publicado o probado algo que no hayas podido verificar.
```
