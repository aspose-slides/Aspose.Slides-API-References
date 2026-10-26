---
title: ContinueWith()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en fortsättning som körs när resultatuppgiften slutförs.
type: docs
weight: 40
url: /sv/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) metod

Skapar en fortsättning som körs när resultatuppgiften slutförs.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Åtgärd att utföra när denna uppgift slutförs och tar emot denna resultatuppgift |

### Returvärde

TaskPtr En ny uppgift som representerar fortsättningen

## Anmärkningar

Fortsättningsåtgärden får detta [ResultTask](../) för att komma åt resultatvärdet

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) metod

Skapar en fortsättning som körs när resultatuppgiften slutförs.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TNewResult | Resultattyp för uppgiftens fortsättning |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Funktion för att få fortsättningsresultatet när denna uppgift slutförs och tar emot denna resultatuppgift |

### Returvärde

RTaskPtr En ny uppgift som representerar fortsättningen

## Anmärkningar

Fortsättningsfunktionen får detta [ResultTask](../) för att komma åt resultatvärdet

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) metod

Skapar en fortsättning som körs när uppgiften slutförs.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Åtgärd att utföra när denna uppgift slutförs |

### Returvärde

TaskPtr En ny uppgift som representerar fortsättningen

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) metod

Skapar en fortsättning som körs när uppgiften slutförs.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | En typ av uppgiftsresultat |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funktion för att få resultatet när denna uppgift slutförs |

### Returvärde

RTaskPtr En ny uppgift som representerar fortsättningen

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)