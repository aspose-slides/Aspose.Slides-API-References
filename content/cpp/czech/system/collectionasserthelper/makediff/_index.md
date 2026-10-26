---
title: MakeDiff()
second_title: Aspose.Slides pro C++ – reference API
description: Vypočítá 'diff' mezi dvěma kolekcemi. Pro každý prvek každé kolekce jako klíč bude výsledná hodnota kladná, pokud se prvek vyskytuje častěji ve \"expected\" kolekci, záporná, pokud se prvek vyskytuje častěji ve \"actual\" kolekci, a nula, pokud se prvek vyskytuje stejně často v obou kolekcích.
type: docs
weight: 1
url: /cs/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method

Vypočítá 'diff' mezi dvěma kolekcemi. Pro každý prvek každé kolekce jako klíč bude výsledná hodnota kladná, pokud se prvek vyskytuje častěji v \"očekávané\" kolekci, záporná, pokud se vyskytuje častěji ve \"skutečné\" kolekci, a nula, pokud se vyskytuje stejně často v obou kolekcích.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ prvku očekávané kolekce. |
| T2 | Typ prvku skutečné kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Očekávaná kolekce. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Skutečná kolekce. |

### Návratová hodnota

Mapa výsledků porovnání pro každou hodnotu podle výše uvedených pravidel.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Dictionary](../../../system.collections.generic/dictionary/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktura [CollectionAssertHelper](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)