---
title: WhenAny()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy feladatot, amely befejeződik, amikor a megadott feladatok bármelyike befejeződik.
type: docs
weight: 209
url: /hu/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) függvény


Létrehoz egy feladatot, amely befejeződik, amikor a megadott feladatok bármelyike befejeződik.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | A feladatok, amelyekre a befejezéshez várni kell. |

### Visszatérési érték

Egy feladat, amely a megadott feladatok egyikének befejezését képviseli.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) függvény


Létrehoz egy feladatot, amely befejeződik, amikor a megadott feladatok bármelyike befejeződik.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | A feladatok, amelyekre a befejezéshez várni kell. |

### Visszatérési érték

Egy feladat, amely a megadott feladatok egyikének befejezését képviseli.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) függvény


Létrehoz egy feladatot, amely befejeződik, amikor a megadott feladatok bármelyike befejeződik.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A befejezett feladat eredményének típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | A feladatok, amelyekre a befejezéshez várni kell. |

### Visszatérési érték

Egy feladat, amely visszaadja az első befejezett feladatot, amikor bármelyik feladat befejeződik.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) függvény


Létrehoz egy feladatot, amely befejeződik, amikor a megadott feladatok bármelyike befejeződik.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A befejezett feladat eredményének típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | A feladatok, amelyekre a befejezéshez várni kell. |

### Visszatérési érték

Egy feladat, amely visszaadja az első befejezett feladatot, amikor bármelyik feladat befejeződik.

## Lásd még

* Típusdefiníció [RTaskPtr](../../system/rtaskptr/)
* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Típusdefiníció [SharedPtr](../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../system/arrayptr/)
* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Névterület [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)