---
title: "System::Threading"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 1002
url: /es/system.threading/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Evento para notificar al hilo en espera que se restablece automáticamente. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [CancellationToken](./cancellationtoken/) | Propaga la notificación de que las operaciones deben cancelarse. Esta clase proporciona un mecanismo para la cancelación cooperativa entre hilos, permitiendo que un hilo notifique a otros que una operación debe cancelarse. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Representa un registro para una devolución de llamada de token de cancelación. |
| [CancellationTokenSource](./cancellationtokensource/) | Una fuente de token de cancelación que se puede usar para desencadenar notificaciones de cancelación. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Evento que puede enviarse al hilo en espera. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [Interlocked](./interlocked/) | Proporciona una API para operaciones seguras en hilos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [ManualResetEvent](./manualresetevent/) | Evento para notificar al hilo en espera que no se restablece automáticamente. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [Monitor](./monitor/) | La clase [Monitor](./monitor/) proporciona un mecanismo que sincroniza el acceso a los objetos. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementación. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementación. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [SynchronizationContext](./synchronizationcontext/) | Proporciona la funcionalidad básica para propagar un contexto de sincronización a través de varias operaciones de sincronización. |
| [Thread](./thread/) | [Thread](./thread/) implementación. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [ThreadPool](./threadpool/) | API de pool [Thread](./thread/) que permite empujar trabajos a la cola para que sean leídos por un pool de hilos trabajador. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [ThreadPoolImpl](./threadpoolimpl/) | Datos internos del pool [Thread](./thread/). Este es un tipo singleton con la gestión de memoria realizada por función(es) de acceso. Nunca debe crear instancias de él directamente. |
| [Timer](./timer/) | Clase [Timer](./timer/) que ejecuta un elemento de trabajo en un hilo separado después de un retraso. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |
| [TimerQueue](./timerqueue/) | Cola que maneja objetos [Timer](./timer/). Esto es solo una implementación. Los objetos [Timer](./timer/) se registran allí por sí mismos, no es necesario hacerlo para utilizarlos; use la API de la clase [Timer](./timer/) en su lugar. Este es un tipo singleton con la gestión de memoria realizada por función(es) de acceso. Nunca debe crear instancias de él directamente. |
| [WaitHandle](./waithandle/) | Clase base de primitiva de espera. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a las funciones como argumento. |

## Estructuras

| Estructura | Descripción |
| --- | --- |
| [Timeout](./timeout/) | Valores especiales de tiempo de espera [Threading](./). Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Establece el estado de apartamento del hilo. |
| [EventResetMode](./eventresetmode/) | Indica cómo se restablece el estado del evento. |
| [ThreadState](./threadstate/) | Estado del hilo. |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | función [Thread](./thread/) con un solo parámetro. |
| [ThreadStart](./threadstart/) | función [Thread](./thread/) sin parámetros. |
| [WaitCallback](./waitcallback/) | Elemento de devolución de llamada que se ejecutará cuando haya un espacio. |
| [TimerCallback](./timercallback/) | Función de devolución de llamada que será invocada por el temporizador. |
| [wait_handle_t](./wait_handle_t/) | Tipo de manejador. |