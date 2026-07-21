---
title: Task()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт Task с действием для выполнения.
type: docs
weight: 1
url: /ru/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) конструктор

Создаёт [Task](../) с действием для выполнения.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Действие для асинхронного выполнения |

## Task::Task(const Action<>\&, const CancellationToken\&) конструктор

Создаёт [Task](../) с действием и токеном отмены.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Действие для асинхронного выполнения |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен для отслеживания запросов отмены |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) конструктор

Создаёт [Task](../) с состоянием действия и объектом состояния.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Действие для выполнения (принимает объект состояния) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Пользовательский объект состояния, передаваемый действию |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) конструктор

Создаёт [Task](../) с состоянием действия, состоянием и токеном отмены.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Действие для выполнения (принимает объект состояния) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Пользовательский объект состояния, передаваемый действию |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Токен для отслеживания запросов отмены |

## Task::Task() конструктор

Внутренний конструктор для создания неинициализированных задач.

```cpp
System::Threading::Tasks::Task::Task()
```

## См. также

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Task](../)
* Класс [CancellationToken](../../../system.threading/cancellationtoken/)
* Класс [Object](../../../system/object/)
* Пространство имён [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)