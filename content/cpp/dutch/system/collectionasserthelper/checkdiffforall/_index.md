---
title: CheckDiffForAll()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of alle collectie-elementen voldoen aan het predicaat.
type: docs
weight: 14
url: /nl/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method

Controleert of alle collectie-elementen voldoen aan het predicaat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicaat om te controleren. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Waarden om te controleren. |

### Retourwaarde

False als de controle faalt voor een element, true als alle slagen.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)