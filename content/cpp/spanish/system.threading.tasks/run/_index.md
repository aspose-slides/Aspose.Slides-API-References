---
title: Run()
second_title: Referencia de API de Aspose.Slides para C++
description: Encola el trabajo especificado para ejecutarse en el grupo de subprocesos y devuelve un manejador Task para ese trabajo.
type: docs
weight: 157
url: /es/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) función


Encola el trabajo especificado para que se ejecute en el grupo de subprocesos y devuelve un manejador [Task](../task/) para ese trabajo.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | El trabajo a ejecutar de forma asíncrona. |

### Valor devuelto

Un [Task](../task/) que representa el trabajo encolado para ejecutarse en el grupo de subprocesos.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) función


Encola el trabajo especificado para que se ejecute en el grupo de subprocesos y devuelve un manejador [Task](../task/) para ese trabajo.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | El trabajo a ejecutar de forma asíncrona. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un token de cancelación que puede usarse para cancelar el trabajo si aún no ha comenzado. |

### Valor devuelto

Un [Task](../task/) que representa el trabajo encolado para ejecutarse en el grupo de subprocesos.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) función


Encola el trabajo especificado para que se ejecute en el grupo de subprocesos y devuelve un proxy para el [Task](../task/) devuelto por la función.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | El trabajo a ejecutar de forma asíncrona, que devuelve un [Task](../task/). |

### Valor devuelto

Un [Task](../task/) que representa un proxy para el [Task](../task/) devuelto por la función.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) función


Encola el trabajo especificado para que se ejecute en el grupo de subprocesos y devuelve un manejador Task<TResult> para ese trabajo.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TResult | El tipo del resultado devuelto por la tarea. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | El trabajo a ejecutar de forma asíncrona. |

### Valor devuelto

Un Task<TResult> que representa el trabajo encolado para ejecutarse en el grupo de subprocesos.

## Ver también

* Definición de tipo [TaskPtr](../../system/taskptr/)
* Definición de tipo [Action](../../system/action/)
* Definición de tipo [RTaskPtr](../../system/rtaskptr/)
* Clase [CancellationToken](../../system.threading/cancellationtoken/)
* Clase [Func](../../system/func/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)