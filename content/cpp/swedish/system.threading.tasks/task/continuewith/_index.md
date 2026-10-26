---
title: ContinueWith()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en fortsättning som körs när uppgiften slutförs.
type: docs
weight: 118
url: /sv/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) metod

Skapar en fortsättning som körs när uppgiften slutförs.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action som ska köras när denna uppgift slutförs |

### Returvärde

TaskPtr En ny uppgift som representerar fortsättningen

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) metod

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
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function som ska hämta resultatet när denna uppgift slutförs |

### Returvärde

RTaskPtr En ny uppgift som representerar fortsättningen

## Se också

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klass [Task](../)
* Klass [Func](../../../system/func/)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)