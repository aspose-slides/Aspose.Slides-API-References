---
title: "System::Threading::Tasks"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 1015
url: /es/system.threading.tasks/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Parallel](./parallel/) | Proporciona soporte para bucles y regiones paralelas. |
| [ParallelLoopResult](./parallelloopresult/) | Proporciona el estado de finalización de un bucle [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Almacena opciones que configuran el funcionamiento de los métodos de la clase [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Una especialización de [Task](./task/) que devuelve un valor de resultado al completarse. |
| [ResultValueTask](./resultvaluetask/) | Representa un tipo híbrido similar a una tarea que puede envolver ya sea un valor de resultado directo o un ResultTask<T>. |
| [Task](./task/) | Representa una operación asíncrona que puede esperarse y combinarse con otras tareas. |
| [TaskScheduler](./taskscheduler/) | Representa un objeto que gestiona el trabajo de bajo nivel de encolar tareas en hilos. |
| [ValueTask](./valuetask/) | Proporciona un resultado esperable de una operación asíncrona. |

## Funciones

| Función | Descripción |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Crea una tarea que se completa después de un retraso temporal. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crea una tarea que se completa después de un retraso temporal y puede cancelarse. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Crea una tarea que ha finalizado debido a una cancelación con el token especificado. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crea una tarea que ha finalizado con una excepción especificada. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Crea una tarea que ha finalizado con una excepción y tipo de resultado especificados. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Crea una tarea que se ha completado correctamente con el resultado especificado. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Encola el trabajo especificado para ejecutarse en el grupo de hilos y devuelve un controlador [Task](./task/) para ese trabajo. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Encola el trabajo especificado para ejecutarse en el grupo de hilos y devuelve un controlador [Task](./task/) para ese trabajo. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Encola el trabajo especificado para ejecutarse en el grupo de hilos y devuelve un proxy para el [Task](./task/) devuelto por la función. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Encola el trabajo especificado para ejecutarse en el grupo de hilos y devuelve un controlador Task<TResult> para ese trabajo. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Espera a que todos los objetos [Task](./task/) proporcionados completen su ejecución. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Espera a que todos los objetos [Task](./task/) proporcionados completen su ejecución. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Espera a que cualquiera de los objetos [Task](./task/) proporcionados complete su ejecución. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Espera a que cualquiera de los objetos [Task](./task/) proporcionados complete su ejecución. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crea una tarea que se completará cuando todas las tareas suministradas se hayan completado. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crea una tarea que se completará cuando todas las tareas suministradas se hayan completado. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crea una tarea que se completará cuando todas las tareas suministradas se hayan completado. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crea una tarea que se completará cuando todas las tareas suministradas se hayan completado. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Crea una tarea que se completará cuando cualquiera de las tareas suministradas se haya completado. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Crea una tarea que se completará cuando cualquiera de las tareas suministradas se haya completado. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Crea una tarea que se completará cuando cualquiera de las tareas suministradas se haya completado. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Crea una tarea que se completará cuando cualquiera de las tareas suministradas se haya completado. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Crea una tarea esperable que cede de forma asíncrona al contexto actual cuando se espera. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |