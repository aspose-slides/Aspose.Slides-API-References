---
title: WhenAny()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт задачу, которая будет завершена, когда любая из предоставленных задач завершится.
type: docs
weight: 209
url: /ru/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) функция


Создаёт задачу, которая будет завершена, когда любая из предоставленных задач завершится.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Задачи, ожидание завершения которых требуется. |

### Возвращаемое значение

Задача, представляющая завершение одной из предоставленных задач.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) функция


Создаёт задачу, которая будет завершена, когда любая из предоставленных задач завершится.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Задачи, ожидание завершения которых требуется. |

### Возвращаемое значение

Задача, представляющая завершение одной из предоставленных задач.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) функция


Создаёт задачу, которая будет завершена, когда любая из предоставленных задач завершится.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результата завершённой задачи. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Задачи, ожидание завершения которых требуется. |

### Возвращаемое значение

Задача, возвращающая первую завершённую задачу, когда любая задача завершается.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) функция


Создаёт задачу, которая будет завершена, когда любая из предоставленных задач завершится.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результата завершённой задачи. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Задачи, ожидание завершения которых требуется. |

### Возвращаемое значение

Задача, возвращающая первую завершённую задачу, когда любая задача завершается.

## См. также

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)