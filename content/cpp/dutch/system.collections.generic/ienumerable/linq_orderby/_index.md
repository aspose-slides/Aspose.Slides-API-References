---
title: LINQ_OrderBy()
second_title: Aspose.Slides voor C++ API-referentie
description: Sorteert de elementen van een reeks in oplopende volgorde op basis van de sleutelwaarden die door keySelector zijn geselecteerd.
type: docs
weight: 209
url: /nl/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) method

Sorteert de elementen van een reeks in oplopende volgorde op basis van de sleutelwaarden die door keySelector zijn geselecteerd.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| keySelector | Een functie om een sleutel uit een element te extraheren. |

### Retourwaarde

Een IOrderedEnumerable waarvan de elementen gesorteerd zijn op basis van een sleutel

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Naamruimte [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)