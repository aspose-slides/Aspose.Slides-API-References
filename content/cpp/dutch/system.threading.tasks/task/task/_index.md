---
title: Task()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een Task met een actie om uit te voeren.
type: docs
weight: 1
url: /nl/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructor

Construeert een [Task](../) met een actie om uit te voeren.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |

## Task::Task(const Action<>\&, const CancellationToken\&) constructor

Construeert een [Task](../) met een actie en een annuleringstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor

Construeert een [Task](../) met een stateful actie en een statusobject.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor

Construeert een [Task](../) met een stateful actie, een status en een annuleringstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task() constructor

Interne constructor voor het maken van niet-geïnitialiseerde taken.

```cpp
System::Threading::Tasks::Task::Task()
```

## Zie ook

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)