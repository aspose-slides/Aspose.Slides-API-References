---
title: ResultValueTask()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт пустой, неинициализированный ResultValueTask.
type: docs
weight: 1
url: /ru/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() конструктор

Создаёт пустой, неинициализированный [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Примечания

Задача не завершена и не содержит результата. Попытка получить результат приведёт к выбросу исключения.

## ResultValueTask::ResultValueTask(const T&) конструктор

Создаёт завершённый [ResultValueTask](../) с указанным результатом.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| result | const T& | Значение результата, которое будет обернуто в завершённую задачу. |

## Примечания

Это создаёт успешно завершённую задачу, которая сразу возвращает значение.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>&) конструктор

Создаёт [ResultValueTask](../) из разделяемого указателя на ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)<T>& | Задача для обёртывания. Может быть null для пустой задачи. |

## Примечания

[ResultValueTask](../) будет представлять состояние и результат предоставленной задачи.

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)