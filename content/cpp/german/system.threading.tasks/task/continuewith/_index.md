---
title: ContinueWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Aufgabe abgeschlossen ist.
type: docs
weight: 118
url: /de/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Aufgabe abgeschlossen ist.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Aktion, die ausgeführt wird, wenn diese Aufgabe abgeschlossen ist |

### Rückgabewert

TaskPtr Eine neue Aufgabe, die die Fortsetzung darstellt

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) Methode

Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Aufgabe abgeschlossen ist.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TResult | Ein Typ des Aufgabenergebnisses |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funktion, um das Ergebnis zu erhalten, wenn diese Aufgabe abgeschlossen ist |

### Rückgabewert

RTaskPtr Eine neue Aufgabe, die die Fortsetzung darstellt

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [Task](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)