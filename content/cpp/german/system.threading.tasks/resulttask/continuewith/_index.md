---
title: ContinueWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Fortsetzung, die ausgeführt wird, wenn die ResultTask abgeschlossen ist.
type: docs
weight: 40
url: /de/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn die ResultTask abgeschlossen ist.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Aktion, die ausgeführt wird, wenn dieser Task abgeschlossen ist, und diesen ResultTask erhält |

### Rückgabewert

TaskPtr Ein neuer Task, der die Fortsetzung repräsentiert

## Anmerkungen

Die Fortsetzungsaktion erhält dieses [ResultTask](../) zum Zugriff auf den Ergebniswert

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn die ResultTask abgeschlossen ist.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TNewResult | Ergebnistyp der Task-Fortsetzung |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Funktion, um das Fortsetzungsergebnis zu erhalten, wenn dieser Task abgeschlossen ist, und diesen ResultTask erhält |

### Rückgabewert

RTaskPtr Ein neuer Task, der die Fortsetzung repräsentiert

## Anmerkungen

Die Fortsetzungsfunktion erhält dieses [ResultTask](../) zum Zugriff auf den Ergebniswert

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn der Task abgeschlossen ist.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Aktion, die ausgeführt wird, wenn dieser Task abgeschlossen ist |

### Rückgabewert

TaskPtr Ein neuer Task, der die Fortsetzung repräsentiert

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn der Task abgeschlossen ist.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Ein Typ des Task-Ergebnisses |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funktion, um das Ergebnis zu erhalten, wenn dieser Task abgeschlossen ist |

### Rückgabewert

RTaskPtr Ein neuer Task, der die Fortsetzung repräsentiert

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultTask](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)