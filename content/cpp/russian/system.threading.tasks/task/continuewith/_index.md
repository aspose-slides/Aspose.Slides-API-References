---
title: ContinueWith()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт продолжение, которое выполняется после завершения задачи.
type: docs
weight: 118
url: /ru/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) метод

Создаёт продолжение, которое выполняется после завершения задачи.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Действие, выполняемое при завершении этой задачи |

### Возвращаемое значение

TaskPtr Новый объект задачи, представляющий продолжение

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) метод


Создаёт продолжение, которое выполняется после завершения задачи.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TResult | Тип результата задачи |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Функция для получения результата при завершении этой задачи |

### Возвращаемое значение

RTaskPtr Новый объект задачи, представляющий продолжение

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)