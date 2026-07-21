---
title: WaitAll()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения выполнения всех предоставленных объектов Task.
type: docs
weight: 170
url: /ru/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) функция

Ожидает завершения выполнения всех предоставленных объектов [Task](../task/).

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Массив экземпляров [Task](../task/), на которых нужно ждать. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Объект [CancellationToken](../../system.threading/cancellationtoken/), наблюдаемый во время ожидания завершения задач. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) функция

Ожидает завершения выполнения всех предоставленных объектов [Task](../task/).

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Массив экземпляров [Task](../task/), на которых нужно ждать. |

## См. также

* Тип [ArrayPtr](../../system/arrayptr/)
* Тип [TaskPtr](../../system/taskptr/)
* Класс [CancellationToken](../../system.threading/cancellationtoken/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)