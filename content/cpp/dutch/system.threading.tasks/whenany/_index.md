---
title: WhenAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een taak die wordt voltooid wanneer een van de opgegeven taken is voltooid.
type: docs
weight: 209
url: /nl/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function

Maakt een taak die wordt voltooid wanneer een van de opgegeven taken is voltooid.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | De taken waarop moet worden gewacht voor voltooiing. |

### Retourwaarde

Een taak die de voltooiing van een van de opgegeven taken vertegenwoordigt.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) function

Maakt een taak die wordt voltooid wanneer een van de opgegeven taken is voltooid.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | De taken waarop moet worden gewacht voor voltooiing. |

### Retourwaarde

Een taak die de voltooiing van een van de opgegeven taken vertegenwoordigt.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function

Maakt een taak die wordt voltooid wanneer een van de opgegeven taken is voltooid.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van het resultaat van de voltooide taak. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | De taken waarop moet worden gewacht voor voltooiing. |

### Retourwaarde

Een taak die de eerst voltooide taak retourneert wanneer een taak voltooid is.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function

Maakt een taak die wordt voltooid wanneer een van de opgegeven taken is voltooid.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van het resultaat van de voltooide taak. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | De taken waarop moet worden gewacht voor voltooiing. |

### Retourwaarde

Een taak die de eerst voltooide taak retourneert wanneer een taak voltooid is.

## Zie ook

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)