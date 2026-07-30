---
title: CollectionAssertHelper
second_title: Aspose.Slides pro C++ API Reference
description: Pomocné API pro operace související s kolekcemi.
type: docs
weight: 1548
url: /cs/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API pro operace související s kolekcí.

```cpp
class CollectionAssertHelper
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Kontroluje, že všechny prvky kolekce splňují predikát. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Kontroluje, že libovolný prvek kolekce splňuje predikát. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializuje dvě kolekce pro reprezentaci zprávy. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Převede kolekci na řetězec sloučením řetězcových reprezentací prvků. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Vypočítá 'diff' mezi dvěma kolekcemi. Pro každý prvek každé kolekce jako klíč bude výsledná hodnota kladná, pokud se prvek vyskytuje častěji ve sbírce "expected", záporná, pokud se prvek vyskytuje častěji ve sbírce "actual", a nula, pokud se prvek vyskytuje stejný početkrát v obou sbírkách. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formátuje řetězec, který bude použit jako text zprávy. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)