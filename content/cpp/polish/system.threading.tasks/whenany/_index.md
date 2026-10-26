---
title: WhenAny()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy zadanie, które zostanie zakończone, gdy dowolne z dostarczonych zadań zostanie ukończone.
type: docs
weight: 209
url: /pl/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funkcja


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Zadania, na które czeka się w celu ich zakończenia. |

### Wartość zwracana

Zadanie reprezentujące zakończenie jednego z podanych zadań.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) funkcja


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Zadania, na które czeka się w celu ich zakończenia. |

### Wartość zwracana

Zadanie reprezentujące zakończenie jednego z podanych zadań.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funkcja


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyniku ukończonego zadania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Zadania, na które czeka się w celu ich zakończenia. |

### Wartość zwracana

Zadanie zwracające pierwsze ukończone zadanie, gdy dowolne zadanie zostanie ukończone.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funkcja


Creates a task that will complete when any of the supplied tasks have completed.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyniku ukończonego zadania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Zadania, na które czeka się w celu ich zakończenia. |

### Wartość zwracana

Zadanie zwracające pierwsze ukończone zadanie, gdy dowolne zadanie zostanie ukończone.

## Zobacz także

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)