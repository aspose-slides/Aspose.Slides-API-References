---
title: WhenAll()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en task som slutförs när alla medföljande tasks är färdiga.
type: docs
weight: 196
url: /sv/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) funktion


Skapar en task som slutförs när alla medföljande tasks är färdiga.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | tasks att vänta på för slutförande. |

### Returvärde

En task som representerar slutförandet av alla medföljande tasks.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funktion


Skapar en task som slutförs när alla medföljande tasks är färdiga.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | tasks att vänta på för slutförande. |

### Returvärde

En task som representerar slutförandet av alla medföljande tasks.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funktion


Skapar en task som slutförs när alla medföljande tasks är färdiga.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen på de slutförda taskarnas resultat. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | tasks att vänta på för slutförande. |

### Returvärde

En task som returnerar en array med alla resultat när alla tasks är färdiga.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funktion


Skapar en task som slutförs när alla medföljande tasks är färdiga.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen på de slutförda taskarnas resultat. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | tasks att vänta på för slutförande. |

### Returvärde

En task som returnerar en array med alla resultat när alla tasks är färdiga.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klass [IEnumerable](../../system.collections.generic/ienumerable/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)