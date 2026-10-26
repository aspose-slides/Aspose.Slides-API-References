---
title: ContinueWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een voortzetting die wordt uitgevoerd wanneer de resultaattaak wordt voltooid.
type: docs
weight: 40
url: /nl/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) methode


Maakt een voortzetting die wordt uitgevoerd wanneer de resultaattaak wordt voltooid.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Actie die moet worden uitgevoerd wanneer deze taak wordt voltooid, waarbij deze resulttaak wordt ontvangen |

### Retourwaarde

TaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt
## Opmerkingen



De voortzettingsactie ontvangt dit [ResultTask](../) om de resultaatwaarde te benaderen 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) methode


Maakt een voortzetting die wordt uitgevoerd wanneer de resultaattaak wordt voltooid.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TNewResult | Resulttype van taakvoortzetting |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Functie om voortzettingsresultaat te verkrijgen wanneer deze taak wordt voltooid, waarbij deze resulttaak wordt ontvangen |

### Retourwaarde

RTaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt
## Opmerkingen



De voortzettingsfunctie ontvangt dit [ResultTask](../) om de resultaatwaarde te benaderen 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) methode


Maakt een voortzetting die wordt uitgevoerd wanneer de taak wordt voltooid.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Actie die moet worden uitgevoerd wanneer deze taak wordt voltooid |

### Retourwaarde

TaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) methode


Maakt een voortzetting die wordt uitgevoerd wanneer de taak wordt voltooid.

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
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Functie om resultaat te verkrijgen wanneer deze taak wordt voltooid |

### Retourwaarde

RTaskPtr Een nieuwe taak die de voortzetting vertegenwoordigt

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultTask](../)
* Klasse [Func](../../../system/func/)
* Naamruimte [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)