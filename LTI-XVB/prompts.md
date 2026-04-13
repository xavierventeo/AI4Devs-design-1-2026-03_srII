# ✍️ Prompts Ejercicio Diseño de un sistema de gestión de candidatos 🔴

Herramientas utilizadas en el ejercicio: **VS Code + Github Copilot**

# Prompt 1: Contexto general y Visión de producto

## Rol esperado

Actúa como un Business Analyst senior con amplia experienca en Recursos Humanos y procesos de contratación de talento que trabajas para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Objetivo del sistema

Definir una primera versión que sea:
- Realista  
- Competitiva  

Con foco en:

- Aumentar la eficiencia de los departamentos de HR  
- Mejorar la colaboración en tiempo real entre recruiters y hiring managers  
- Incorporar automatizaciones  
- Integrar asistencia de IA en tareas clave del proceso de selección  

## Funcionalidades básicas del sistema
1.- Creación de ofertas de empleo  
2.- Publicados en portales de empleo, sitios web, redes sociales, etc.  
3.- Recepción de solicitudes de empleo  
4.- Revisión de solicitudes  
5.- Realización de pruebas en línea  
6.- Programación de entrevistas  
7.- Contratación de candidatos seleccionados  


## Requisitos de salida

Las respuestas deben cumplir con:
  
- Tono: Claro, académico y profesional  
- Enfoque: Solución realista, coherente y bien estructurada  
- Justificación: Evitar explicaciones vagas, todas las decisiones deben estar justificadas  
- Diagramas: Usar siempre formato **Mermaid**  
- Formato final: Todo debe poder integrarse en un único archivo `.md`  

## Resultado

Genera un fichero markdown LTI-XVB.md en la carpeta docs

- Descripción breve del software LTI, valor añadido y ventajas competitivas.
- Explicación de las funciones principales.


# Prompt 2: Añadir un diagrama Lean Canvas para entender el modelo de negocio.

## Rol

Actúa como Product manager senior con amplia experienca en Recursos Humanos y procesos de contratación de talento que colaboras para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Contexto
Toma como base el documento #file:LTI-XVB.md para generar un diagrama Lean Canvas para entender el modelo de negocio.

## Resultado
Genera un diagrama Lean Canvas que pueda ser visible dentro del documento LTI-XVB.md

# Prompt 3: Descripción de los 3 casos de uso principales, con el diagrama asociado a cada uno.

## Rol
Actúa como un Product Owner experto con amplia experienca en Recursos Humanos y procesos de contratación de talento que colaboras para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Contexto
Toma como base el documento #file:LTI-XVB.md para entender el modelo de negocio del sistema ATS-LTI

## Objetivo
Describir y documentar de los 3 casos de uso principales:
1.- Creación de ofertas de empleo  
2.- Publicados en portales de empleo, sitios web, redes sociales, etc.  
3.- Recepción de solicitudes de empleo 

## Instrucciones
Para cada caso de uso:

- Proporciona una descripción del caso de uso) en formato markdown
- Genera un diagrama en formato **Mermaid** 

## Resultado
Genera el resultado al final del documento LTI-XVB.md 


# Prompt 4: Modelo de datos que cubra entidades, atributos (nombre y tipo) y relaciones

## Rol
Actúa como un Arquitecto de sofware experto con amplia experienca que colaboras para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Contexto
Toma como base el documento #file:LTI-XVB.md para entender el modelo de negocio y casos de uso principales del sistema ATS-LTI

## Objetivo
Generar el modelo de dato de las principales entidades para el sistema ATS LTI

## Instrucciones
- Genera un diagrama con las diferentes entidades con los atributos esenciales (nombre y tipo) y las relaciones entre entidaddes en formato **Mermaid**
- Describe las diferentes entidades que has generado en el diagrama en formato
- Describe qué otras entidades del modelo de datos son importantes en el sistema ATS-LTI

## Resultado
Genera el resultado al final del documento LTI-XVB.md 

# Prompt 5: Diseño del sistema a alto nivel, tanto explicado como diagrama adjunto

## Rol
Actúa como un Arquitecto de sofware experto con amplia experienca que colaboras para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Contexto
Toma como base el documento #file:LTI-XVB.md para entender el modelo de negocio y casos de uso principales del sistema ATS-LTI

## Objetivo
Generar el modelo de dato de las principales entidades para el sistema ATS LTI

## Instrucciones
- Genera un diagrama con las diferentes entidades con los atributos esenciales (nombre y tipo) y las relaciones entre entidaddes en formato **Mermaid**
- Describe las diferentes entidades que has generado en el diagrama en formato
- Describe qué otras entidades del modelo de datos son importantes en el sistema ATS-LTI

## Resultado
Genera el resultado al final del documento LTI-XVB.md 


# Prompt 6: Diagrama C4 que llegue en profundidad a uno de los componentes del sistema,

## Rol
Actúa como un Arquitecto de sofware experto con amplia experienca que colaboras para diseñar la primera versión de un **ATS (Applicant Tracking System)** llamado **LTI** para una startup. 

## Contexto
Toma como base el documento #file:LTI-XVB.md para entender el modelo de negocio, casos de uso principales y el diseño de la arquitectura del sistema ATS-LTI

## Instrucciones
Genera los diagrama C4 el sistema ATS LTI con los siguientes niveles: Context, Containers, Components.
Y que llegue a nivel Code sólo uno de los componentes principales


## Resultado
Genera el resultado al final del documento LTI-XVB.md


