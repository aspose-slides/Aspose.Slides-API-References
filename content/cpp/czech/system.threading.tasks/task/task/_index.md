---
title: Task()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří Task s akcí k provedení.
type: docs
weight: 1
url: /cs/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) konstruktor

Vytvoří [Task](../) s akcí k provedení.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |

## Task::Task(const Action<>\&, const CancellationToken\&) konstruktor

Vytvoří [Task](../) s akcí a tokenem pro zrušení.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) konstruktor

Vytvoří [Task](../) se stavovou akcí a stavovým objektem.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) konstruktor

Vytvoří [Task](../) se stavovou akcí, stavem a tokenem pro zrušení.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task() konstruktor

Interní konstruktor pro vytvoření neinicializovaných úkolů.

```cpp
System::Threading::Tasks::Task::Task()
```

## Viz také

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Task](../)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [Object](../../../system/object/)
* Jmenný prostor [System::Threading::Tasks](../../)
* Knihovna [Aspose.Slides](../../../)