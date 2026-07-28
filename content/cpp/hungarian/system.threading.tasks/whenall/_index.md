---
title: WhenAll()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződik.
type: docs
weight: 196
url: /hu/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function

Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződik.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | A feladatok, amelyek befejezésére várakozni kell. |

### Visszatérési érték

Egy feladat, amely az összes megadott feladat befejezését jelképezi.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function

Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződik.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | A feladatok, amelyek befejezésére várakozni kell. |

### Visszatérési érték

Egy feladat, amely az összes megadott feladat befejezését jelképezi.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function

Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződik.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A befejezett feladatok eredményeinek típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | A feladatok, amelyek befejezésére várakozni kell. |

### Visszatérési érték

Egy feladat, amely az összes eredményt tartalmazó tömböt ad vissza, amikor az összes feladat befejeződik.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function

Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződik.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A befejezett feladatok eredményeinek típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | A feladatok, amelyek befejezésére várakozni kell. |

### Visszatérési érték

Egy feladat, amely az összes eredményt tartalmazó tömböt ad vissza, amikor az összes feladat befejeződik.

## Lásd még

* Típusdefiníció [TaskPtr](../../system/taskptr/)
* Típusdefiníció [ArrayPtr](../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../system/sharedptr/)
* Típusdefiníció [RTaskPtr](../../system/rtaskptr/)
* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)