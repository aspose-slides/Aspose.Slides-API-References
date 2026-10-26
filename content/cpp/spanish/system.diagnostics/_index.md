---
title: "System::Diagnostics"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 469
url: /es/system.diagnostics/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Proporciona información sobre la versión del archivo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [PerformanceCounter](./performancecounter/) | Clase ficticia para que el código traducido que usa PerformanceCounter compile. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [Process](./process/) | Encapsula información y manipulación de procesos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [ProcessStartInfo](./processstartinfo/) | Describe los parámetros de inicio del proceso. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [StackFrame](./stackframe/) | Obtiene información sobre un único marco de pila. Solo MSVS. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [StackTrace](./stacktrace/) | Colección de marcos de pila. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [Stopwatch](./stopwatch/) | Permite la medición del tiempo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |
| [TraceListener](./tracelistener/) | Interfaz para reaccionar a información de depuración y trazado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a las funciones como argumento. |

## Estructuras

| Estructura | Descripción |
| --- | --- |
| [Debug](./debug/) | Colección de métodos de depuración que permiten enviar información de depuración a los oyentes registrados. Todas las funciones de salida funcionan solo en [Debug](./debug/). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Debugger](./debugger/) | Interfaz [Debugger](./debugger/). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [Trace](./trace/) | Proporciona una interfaz para acceder al rastreo del depurador (si lo hay). Funciona solo en modo [Debug](./debug/). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Estilo de la ventana del proceso. |
| [TraceEventType](./traceeventtype/) | Identifica el tipo de evento que ha causado el rastreo. |
| [TraceLevel](./tracelevel/) | Especifica qué mensajes se deben emitir para las clases [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) y System.Diagnostics.TraceSwitch. |

## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Tipo puntero. |