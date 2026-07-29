---
title: Task()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en Task med en åtgärd att utföra.
type: docs
weight: 1
url: /sv/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) konstruktor


Skapar en [Task](../) med en åtgärd att utföra.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Åtgärden som ska utföras asynkront |

## Task::Task(const Action<>\&, const CancellationToken\&) konstruktor


Skapar en [Task](../) med en åtgärd och avbrottstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Åtgärden som ska utföras asynkront |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token för att övervaka avbrottsförfrågningar |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) konstruktor


Skapar en [Task](../) med en tillståndsbaserad åtgärd och ett tillståndsobjekt.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Åtgärden som ska utföras (accepterar tillståndsobjekt) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Användardefinierat tillståndsobjekt som skickas till åtgärden |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) konstruktor


Skapar en [Task](../) med en tillståndsbaserad åtgärd, tillstånd och avbrottstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Åtgärden som ska utföras (accepterar tillståndsobjekt) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Användardefinierat tillståndsobjekt som skickas till åtgärden |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token för att övervaka avbrottsförfrågningar |

## Task::Task() konstruktor


Intern konstruktor för att skapa oinitialiserade uppgifter.

```cpp
System::Threading::Tasks::Task::Task()
```

## Se även

* Typdefinition [Action](../../../system/action/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Task](../)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [Object](../../../system/object/)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)