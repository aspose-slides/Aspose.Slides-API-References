---
title: WhenAny()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en uppgift som slutförs när någon av de angivna uppgifterna har slutförts.
type: docs
weight: 209
url: /sv/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funktion

Skapar en uppgift som slutförs när någon av de angivna uppgifterna har slutförts.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Uppgifterna att vänta på för slutförande. |

### Returvärde

En uppgift som representerar slutförandet av en av de angivna uppgifterna.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) funktion

Skapar en uppgift som slutförs när någon av de angivna uppgifterna har slutförts.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Uppgifterna att vänta på för slutförande. |

### Returvärde

En uppgift som representerar slutförandet av en av de angivna uppgifterna.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funktion

Skapar en uppgift som slutförs när någon av de angivna uppgifterna har slutförts.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen för den slutförda uppgiftens resultat. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Uppgifterna att vänta på för slutförande. |

### Returvärde

En uppgift som returnerar den första slutförda uppgiften när någon uppgift slutförs.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funktion

Skapar en uppgift som slutförs när någon av de angivna uppgifterna har slutförts.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen för den slutförda uppgiftens resultat. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Uppgifterna att vänta på för slutförande. |

### Returvärde

En uppgift som returnerar den första slutförda uppgiften när någon uppgift slutförs.

## Se också

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* klass [IEnumerable](../../system.collections.generic/ienumerable/)
* namnrymde [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)