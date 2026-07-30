---
title: CollectionsToMsg()
second_title: Aspose.Slides pro C++ API Reference
description: Serializuje dvě kolekce pro reprezentaci zprávy.
type: docs
weight: 53
url: /cs/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metoda

Serializuje dvě kolekce pro reprezentaci zprávy.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Očekávaný typ prvku kolekce. |
| T2 | Skutečný typ prvku kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Vlastní řetězec, který je vložen před očekávanou hodnotu ve výsledné zprávě |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Očekávaná kolekce. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Skutečná kolekce. |

### Návratová hodnota

Uživatelsky přívětivá zpráva o obsahu kolekcí.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktura [CollectionAssertHelper](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)