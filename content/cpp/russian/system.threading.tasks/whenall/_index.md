---
title: WhenAll()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт задачу, которая завершится, когда все предоставленные задачи завершатся.
type: docs
weight: 196
url: /ru/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) функция


Создаёт задачу, которая завершится, когда все предоставленные задачи завершатся.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Задачи, по которым следует ждать завершения. |

### Возвращаемое значение

Задача, представляющая завершение всех предоставленных задач.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) функция


Создаёт задачу, которая завершится, когда все предоставленные задачи завершатся.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Задачи, по которым следует ждать завершения. |

### Возвращаемое значение

Задача, представляющая завершение всех предоставленных задач.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) функция


Создаёт задачу, которая завершится, когда все предоставленные задачи завершатся.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результатов завершённых задач. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Задачи, по которым следует ждать завершения. |

### Возвращаемое значение

Задача, возвращающая массив всех результатов, когда все задачи завершатся.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) функция


Создаёт задачу, которая завершится, когда все предоставленные задачи завершатся.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результатов завершённых задач. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Задачи, по которым следует ждать завершения. |

### Возвращаемое значение

Задача, возвращающая массив всех результатов, когда все задачи завершатся.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)