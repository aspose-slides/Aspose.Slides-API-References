---
title: WaitAny()
second_title: Aspose.Slides для C++ API Reference
description: Ожидает завершения выполнения любого из предоставленных объектов Task.
type: docs
weight: 183
url: /ru/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function


Ожидает завершения выполнения любого из предоставленных [Task](../task/) объектов.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Массив экземпляров [Task](../task/), на которых необходимо ожидать. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Объект [CancellationToken](../../system.threading/cancellationtoken/), наблюдаемый во время ожидания завершения задач. |

### Возвращаемое значение

Индекс завершённой задачи в массиве задач.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function


Ожидает завершения выполнения любого из предоставленных [Task](../task/) объектов.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Массив экземпляров [Task](../task/), на которых необходимо ожидать. |

### Возвращаемое значение

Индекс завершённой задачи в массиве задач.

## См. также

* Типовое определение [ArrayPtr](../../system/arrayptr/)
* Типовое определение [TaskPtr](../../system/taskptr/)
* Класс [CancellationToken](../../system.threading/cancellationtoken/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)