---
title: ContinueWith()
second_title: Aspose.Slides para referencia de API de C++
description: Crea una continuación que se ejecuta cuando la tarea de resultado se completa.
type: docs
weight: 40
url: /es/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) método

Crea una continuación que se ejecuta cuando la tarea de resultado se completa.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action a ejecutar cuando esta tarea se completa, recibiendo esta tarea de resultado |

### Valor devuelto

TaskPtr Una nueva tarea que representa la continuación

## Observaciones



La acción de continuación recibe este [ResultTask](../) para acceder al valor del resultado 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) método


Crea una continuación que se ejecuta cuando la tarea de resultado se completa.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TNewResult | Tipo de resultado de la continuación de tarea |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Function para obtener el resultado de la continuación cuando esta tarea se completa, recibiendo esta tarea de resultado |

### Valor devuelto

RTaskPtr Una nueva tarea que representa la continuación

## Observaciones



La función de continuación recibe este [ResultTask](../) para acceder al valor del resultado 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) método


Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action a ejecutar cuando esta tarea se completa |

### Valor devuelto

TaskPtr Una nueva tarea que representa la continuación

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) método


Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | Un tipo de resultado de tarea |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function para obtener el resultado cuando esta tarea se completa |

### Valor devuelto

RTaskPtr Una nueva tarea que representa la continuación

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Clase [ResultTask](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)