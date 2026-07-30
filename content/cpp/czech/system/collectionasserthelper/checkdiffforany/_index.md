---
title: CheckDiffForAny()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, že libovolný prvek kolekce splňuje predikát.
type: docs
weight: 27
url: /cs/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


Kontroluje, že libovolný prvek kolekce splňuje predikát.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikát k ověření. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Hodnoty k ověření. |

### Návratová hodnota

True pokud kontrola uspěje pro libovolný prvek, false pokud všechny projdou.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [ICollection](../../../system.collections.generic/icollection/)
* Struktura [CollectionAssertHelper](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)