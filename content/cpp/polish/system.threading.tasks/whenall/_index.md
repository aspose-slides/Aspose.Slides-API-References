---
title: WhenAll()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy zadanie, które zostanie zakończone, gdy wszystkie dostarczone zadania zostaną ukończone.
type: docs
weight: 196
url: /pl/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) funkcja

Tworzy zadanie, które zostanie zakończone, gdy wszystkie dostarczone zadania zostaną ukończone.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Zadania, na które należy czekać, aby zakończyły się. |

### Wartość zwracana

Zadanie, które reprezentuje zakończenie wszystkich dostarczonych zadań.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funkcja

Tworzy zadanie, które zostanie zakończone, gdy wszystkie dostarczone zadania zostaną ukończone.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Zadania, na które należy czekać, aby zakończyły się. |

### Wartość zwracana

Zadanie, które reprezentuje zakończenie wszystkich dostarczonych zadań.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funkcja

Tworzy zadanie, które zostanie zakończone, gdy wszystkie dostarczone zadania zostaną ukończone.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyników zakończonych zadań. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Zadania, na które należy czekać, aby zakończyły się. |

### Wartość zwracana

Zadanie zwracające tablicę wszystkich wyników po zakończeniu wszystkich zadań.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funkcja

Tworzy zadanie, które zostanie zakończone, gdy wszystkie dostarczone zadania zostaną ukończone.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyników zakończonych zadań. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Zadania, na które należy czekać, aby zakończyły się. |

### Wartość zwracana

Zadanie zwracające tablicę wszystkich wyników po zakończeniu wszystkich zadań.

## Zobacz także

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)