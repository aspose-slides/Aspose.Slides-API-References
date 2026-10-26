---
title: CheckDiffForAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een willekeurig collectie-element aan het predicaat voldoet.
type: docs
weight: 27
url: /nl/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method

Controleert of een willekeurig collectie-element aan het predicaat voldoet.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicaat om te controleren. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Waarden om te controleren. |

### Retourwaarde

True als de controle slaagt voor een element, false als alle elementen slagen.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)