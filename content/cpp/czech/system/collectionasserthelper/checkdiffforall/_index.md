---
title: CheckDiffForAll()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Kontroluje, že všechny prvky kolekce splňují predikát.
type: docs
weight: 14
url: /cs/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metoda

Kontroluje, že všechny prvky kolekce splňují predikát.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikát k ověření. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Hodnoty k ověření. |

### Návratová hodnota

False, pokud kontrola selže pro kterýkoli prvek, true, pokud všechny projdou.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* třída [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* jmenný prostor [System](../../)
* knihovna [Aspose.Slides](../../../)