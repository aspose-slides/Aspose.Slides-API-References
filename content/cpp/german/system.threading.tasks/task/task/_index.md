---
title: Task()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert ein Task mit einer auszuführenden Aktion.
type: docs
weight: 1
url: /de/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) Konstruktor

Erstellt ein [Task](../) mit einer auszuführenden Aktion.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Die Aktion, die asynchron ausgeführt wird |

## Task::Task(const Action<>\&, const CancellationToken\&) Konstruktor

Erstellt ein [Task](../) mit einer Aktion und einem Abbruch-Token.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Die Aktion, die asynchron ausgeführt wird |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token zur Überwachung von Abbruchanforderungen |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) Konstruktor

Erstellt ein [Task](../) mit einer zustandsbehafteten Aktion und einem Zustandsobjekt.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Die Aktion, die ausgeführt wird (akzeptiert Zustandsobjekt) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Vom Benutzer definiertes Zustandsobjekt, das an die Aktion übergeben wird |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) Konstruktor

Erstellt ein [Task](../) mit zustandsbehafteter Aktion, Zustand und Abbruch-Token.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Die Aktion, die ausgeführt wird (akzeptiert Zustandsobjekt) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Vom Benutzer definiertes Zustandsobjekt, das an die Aktion übergeben wird |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token zur Überwachung von Abbruchanforderungen |

## Task::Task() Konstruktor

Interner Konstruktor zum Erzeugen nicht initialisierter Tasks.

```cpp
System::Threading::Tasks::Task::Task()
```

## Siehe auch

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)