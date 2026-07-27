---
title: WhenAny()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado.
type: docs
weight: 209
url: /es/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) función


Crea una tarea que se completará cuando cualquiera de las tareas proporcionadas haya finalizado.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Las tareas a esperar para su finalización. |

### Valor devuelto

Una tarea que representa la finalización de una de las tareas suministradas.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) función


Crea una tarea que se completará cuando cualquiera de las tareas proporcionadas haya finalizado.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Las tareas a esperar para su finalización. |

### Valor devuelto

Una tarea que representa la finalización de una de las tareas suministradas.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) función


Crea una tarea que se completará cuando cualquiera de las tareas proporcionadas haya finalizado.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea completada. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Las tareas a esperar para su finalización. |

### Valor devuelto

Una tarea que devuelve la primera tarea completada cuando cualquiera de las tareas finaliza.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) función


Crea una tarea que se completará cuando cualquiera de las tareas proporcionadas haya finalizado.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea completada. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Las tareas a esperar para su finalización. |

### Valor devuelto

Una tarea que devuelve la primera tarea completada cuando cualquiera de las tareas finaliza.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)