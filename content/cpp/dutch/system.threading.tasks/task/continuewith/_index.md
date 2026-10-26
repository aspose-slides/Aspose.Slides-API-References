---
title: ContinueWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een voortzetting die wordt uitgevoerd wanneer de taak voltooid is.
type: docs
weight: 118
url: /nl/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) methode

Maakt een voortzetting die wordt uitgevoerd wanneer de taak voltooid is.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Actie die moet worden uitgevoerd wanneer deze taak voltooid is |

### Retourwaarde

TaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) methode

Maakt een voortzetting die wordt uitgevoerd wanneer de taak voltooid is.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Een type van taakresultaat |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Functie om het resultaat te verkrijgen wanneer deze taak voltooid is |

### Retourwaarde

RTaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)