---
title: ContinueWith()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una continuación que se ejecuta cuando la tarea se completa.
type: docs
weight: 118
url: /es/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) método

Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Acción a ejecutar cuando esta tarea se complete |

### Valor devuelto

TaskPtr Una nueva tarea que representa la continuación

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) método

Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | Un tipo de resultado de la tarea |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Función para obtener el resultado cuando esta tarea se complete |

### Valor devuelto

RTaskPtr Una nueva tarea que representa la continuación

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Clase [Task](../)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)