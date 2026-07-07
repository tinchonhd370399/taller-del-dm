
# Arquitectura del Taller del DM

## Propósito

Esta bóveda es el sistema central para aprender, preparar y dirigir campañas de Dungeons & Dragons.

## Principios

- Primero se diseña la arquitectura; después se crea contenido.
    
- Cada nota, carpeta y plantilla debe tener un propósito concreto.
    
- Se prioriza la utilidad inmediata sobre completar estructuras vacías.
    
- El sistema debe poder reutilizarse entre campañas.
    
- La estructura puede refactorizarse cuando deje de servir.
    

## Responsabilidad de cada herramienta

- **Obsidian:** conocimiento y gestión de campañas.
    
- **Excalidraw:** diagramas, relaciones, mapas conceptuales y bocetos rápidos.
    
- **Krita:** arte final, recursos visuales e imprimibles.
    

## Objetivo durante una partida

Encontrar reglas, NPC, lugares, sesiones y recursos rápidamente para poder narrar, improvisar y reaccionar a los jugadores.

## Entender los símbolos básicos de formato de Obsidian antes de seguir construyendo el Taller del DM.

## Instrucciones concretas

No modifiques nada todavía. Solo mirá esta guía:

| Símbolo              | Qué hace                               | Ejemplo escrito         | Cómo se ve                                     |
| -------------------- | -------------------------------------- | ----------------------- | ---------------------------------------------- |
| `#`                  | Título principal de una nota           | `# Centro de campaña`   | Centro de campaña grande                       |
| `##`                 | Subtítulo o sección dentro de la nota  | `## Estado actual`      | Estado actual más chico                        |
| `###`                | Sub-sección dentro de una sección      | `### Próxima sesión`    | Próxima sesión todavía más chico               |
| `**texto**`          | Pone texto en **negrita**              | `**Campaña:**`          | **Campaña:**                                   |
| `-`                  | Crea un elemento de lista              | `- Preparar al villano` | • Preparar al villano                          |
| `- [ ]`              | Crea una tarea sin completar           | `- [ ] Preparar mapa`   | ☐ Preparar mapa                                |
| `- [x]`              | Marca una tarea como completada        | `- [x] Preparar mapa`   | ☑ Preparar mapa                                |
| `[[Nombre de nota]]` | Crea un enlace a otra nota de Obsidian | `[[Notas de sesión]]`   | Un enlace clickeable llamado “Notas de sesión” |
| `>`                  | Crea una cita o bloque destacado       | `> Recordar esta pista` | Una línea resaltada al costado                 |

### Sobre `[[Nombre de nota]]`

Ese formato significa: “esta palabra es una nota conectada con otra nota”.

Por ejemplo:

```
[[Notas de sesión]]
```

Puede funcionar de dos maneras:

- Si la nota **ya existe**, al hacer clic se abre.
- Si la nota **no existe**, Obsidian te muestra el nombre como enlace y, al hacer clic, crea una nota nueva con ese nombre.

Entonces no hace falta saber crear primero las notas enlazadas: el enlace puede crearlas cuando las necesites.

Por ahora, no vamos a usar enlaces ni escribir el contenido del Centro de campaña. Primero quiero que puedas reconocer qué estás leyendo y qué estás escribiendo en Obsidian.

Cuando te quede claro, respondeme con una de estas dos opciones: **“Entendí”** o **“Explicame [símbolo] otra vez”**.

-----------------
-

==Lo único que sí instalaría en Obsidian==

==Acá sí creo que vale la pena invertir un rato.==

==Hay plugins que son prácticamente obligatorios para un proyecto como el tuyo:==

==Templater → para crear fichas de NPC, monstruos, sesiones y lugares con un clic.==
==Dataview → para generar listas automáticas (por ejemplo, "todos los NPC de Baldur's Gate").==
==Excalidraw → este es el que creo que cambia todo para vos.==

==¿Por qué Excalidraw?==

==Porque combina lo mejor de los dos mundos.==

==Dentro de Obsidian podés:==

==dibujar con el lápiz;==
==hacer mapas conceptuales;==
==crear diagramas;==
==conectar NPC;==
==hacer árboles genealógicos;==
==organizar conspiraciones;==
==dibujar dungeons sencillas.==

==Y lo mejor: todo queda integrado en la misma bóveda, con enlaces a tus notas.==

==Eso evita el problema de tener dibujos desperdigados en otra aplicación.==

==---==

==Mi propuesta para el proyecto==

==Creo que deberíamos fijar una regla desde el principio:==

==Cada herramienta debe tener una única responsabilidad.==

==Así evitamos duplicar información.==

|Herramienta|Responsabilidad|
|---|---|
|Obsidian|Todo el conocimiento de la campaña.|
|Excalidraw (plugin de Obsidian)|Diagramas, mapas conceptuales y bocetos rápidos con lápiz.|
|Krita|Arte y material que va a imprimirse o que requiere un acabado visual.|

==Esa separación hace que siempre sepas dónde va cada cosa.==

==---==

==Una idea que me entusiasma para este proyecto==

==Creo que no deberíamos limitarnos a "organizar una campaña". Podemos diseñar un sistema de dirección. Algo que tenga estructura, plantillas, flujos de trabajo y ayudas memoria pensadas específicamente para vos.==

==Mi objetivo sería que, cuando llegue el día de dirigir, no tengas que pensar "¿dónde estaba esa regla?", sino que todo esté organizado para encontrarlo en segundos. Si logramos eso, vas a poder concentrarte en lo importante: narrar, reaccionar a los jugadores y disfrutar la partida.==

==Y creo que podemos construir ese sistema paso a paso, empezando por la bóveda de Obsidian. Ahí es donde pondría nuestro siguiente esfuerzo.==
