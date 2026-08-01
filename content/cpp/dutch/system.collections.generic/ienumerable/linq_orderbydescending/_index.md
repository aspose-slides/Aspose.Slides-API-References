---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides voor C++ API-referentie
description: Sorteert de elementen van een reeks in aflopende volgorde volgens de sleutelwaarden die door keySelector zijn geselecteerd.
type: docs
weight: 222
url: /nl/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) methode

Sorteert de elementen van een reeks in aflopende volgorde op basis van de sleutelwaarden die door keySelector zijn geselecteerd.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| keySelector | Een functie om een sleutel uit een element te halen. |

### Retourwaarde

Een IOrderedEnumerable waarvan de elementen zijn gesorteerd in aflopende volgorde van de sleutel

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) methode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Naamruimte [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)