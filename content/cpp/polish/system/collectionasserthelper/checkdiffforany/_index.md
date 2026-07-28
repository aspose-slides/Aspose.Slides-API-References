---
title: CheckDiffForAny()
second_title: Aspose.Slides dla C++ – referencja API
description: Sprawdza, czy dowolny element kolekcji spełnia predykat.
type: docs
weight: 27
url: /pl/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


Sprawdza, czy dowolny element kolekcji spełnia predykat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predykat do sprawdzenia. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Wartości do sprawdzenia. |

### Wartość zwracana

Prawda, jeśli sprawdzenie zakończy się sukcesem dla dowolnego elementu, fałsz, jeśli wszystkie przejdą.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)