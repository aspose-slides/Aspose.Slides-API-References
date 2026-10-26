---
title: WhenAll()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.
type: docs
weight: 196
url: /es/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) función


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Las tareas que se esperan para su finalización. |

### Valor devuelto

Una tarea que representa la finalización de todas las tareas suministradas.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) función


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Las tareas que se esperan para su finalización. |

### Valor devuelto

Una tarea que representa la finalización de todas las tareas suministradas.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) función


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de los resultados de las tareas completadas. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Las tareas que se esperan para su finalización. |

### Valor devuelto

Una tarea que devuelve una matriz con todos los resultados cuando todas las tareas se completan.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) función


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de los resultados de las tareas completadas. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Las tareas que se esperan para su finalización. |

### Valor devuelto

Una tarea que devuelve una matriz con todos los resultados cuando todas las tareas se completan.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Clase [IEnumerable](../../system.collections.generic/ienumerable/)
* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)