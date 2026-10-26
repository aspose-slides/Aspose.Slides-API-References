---
title: WhenAll()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een taak die wordt voltooid wanneer alle opgegeven taken zijn voltooid.
type: docs
weight: 196
url: /nl/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) functie

Maakt een taak die wordt voltooid wanneer alle opgegeven taken zijn voltooid.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | De taken waarop gewacht moet worden tot voltooiing. |

### Retourwaarde

Een taak die de voltooiing van alle opgegeven taken vertegenwoordigt.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) functie

Maakt een taak die wordt voltooid wanneer alle opgegeven taken zijn voltooid.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | De taken waarop gewacht moet worden tot voltooiing. |

### Retourwaarde

Een taak die de voltooiing van alle opgegeven taken vertegenwoordigt.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) functie

Maakt een taak die wordt voltooid wanneer alle opgegeven taken zijn voltooid.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van de resultaten van de voltooide taken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | De taken waarop gewacht moet worden tot voltooiing. |

### Retourwaarde

Een taak die een array van alle resultaten retourneert wanneer alle taken zijn voltooid.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) functie

Maakt een taak die wordt voltooid wanneer alle opgegeven taken zijn voltooid.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van de resultaten van de voltooide taken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | De taken waarop gewacht moet worden tot voltooiing. |

### Retourwaarde

Een taak die een array van alle resultaten retourneert wanneer alle taken zijn voltooid.

## Zie ook

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Naamruimte [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)