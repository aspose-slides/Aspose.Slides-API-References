---
title: ContinueWith()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy folytatást, amely a feladat befejezésekor fut le.
type: docs
weight: 118
url: /hu/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) metódus

Létrehoz egy folytatást, amely a feladat befejezésekor fut le.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | A végrehajtandó művelet, amikor ez a feladat befejeződik |

### Visszatérési érték

TaskPtr Egy új feladat, amely a folytatást képviseli

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) metódus

Létrehoz egy folytatást, amely a feladat befejezésekor fut le.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A feladat eredményének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | A függvény, amely az eredményt lekéri, amikor ez a feladat befejeződik |

### Visszatérési érték

RTaskPtr Egy új feladat, amely a folytatást képviseli

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)