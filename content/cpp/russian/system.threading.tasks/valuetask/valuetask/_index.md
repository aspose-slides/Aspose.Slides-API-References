---
title: ValueTask()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт пустой, неинициализированный ValueTask.
type: docs
weight: 1
url: /ru/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() конструктор

Создаёт пустой, неинициализированный [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Примечание

Задача не завершена и не содержит результата. Попытка получить результат приведёт к выбросу исключения.

## ValueTask::ValueTask(const TaskPtr\&) конструктор

Создаёт [ValueTask](../) из разделяемого указателя на [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Задача для обертывания. Может быть null для пустой задачи. |

## Примечание

[ValueTask](../) будет представлять состояние предоставленной задачи.

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)