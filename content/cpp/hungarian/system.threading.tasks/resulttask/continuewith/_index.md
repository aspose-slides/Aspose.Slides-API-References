---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehoz egy folytatást, amely akkor hajtódik végre, amikor az eredményfeladat befejeződik.
type: docs
weight: 40
url: /hu/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) metódus

Létrehoz egy folytatást, amely akkor hajtódik végre, amikor az eredményfeladat befejeződik.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Művelet, amely akkor hajtódik végre, amikor ez a feladat befejeződik, és megkapja ezt az eredményfeladatot |

### Visszatérési érték

TaskPtr Új feladat, amely a folytatást képviseli

## Megjegyzések

A folytatási művelet megkapja ezt a [ResultTask](../)-t az eredményérték eléréséhez

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) metódus

Létrehoz egy folytatást, amely akkor hajtódik végre, amikor az eredményfeladat befejeződik.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TNewResult | A feladatfolytatás eredménytípusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Függvény, amely a folytatási eredményt adja vissza, amikor ez a feladat befejeződik, és megkapja ezt az eredményfeladatot |

### Visszatérési érték

RTaskPtr Új feladat, amely a folytatást képviseli

## Megjegyzések

A folytatási függvény megkapja ezt a [ResultTask](../)-t az eredményérték eléréséhez

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) metódus

Létrehoz egy folytatást, amely akkor hajtódik végre, amikor a feladat befejeződik.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Művelet, amely akkor hajtódik végre, amikor ez a feladat befejeződik |

### Visszatérési érték

TaskPtr Új feladat, amely a folytatást képviseli

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) metódus

Létrehoz egy folytatást, amely akkor hajtódik végre, amikor a feladat befejeződik.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A feladat eredményének típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Függvény, amely az eredményt adja, amikor ez a feladat befejeződik |

### Visszatérési érték

RTaskPtr Új feladat, amely a folytatást képviseli

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)