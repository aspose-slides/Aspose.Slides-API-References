---
title: LINQ_ThenBy()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een nadere sortering uit van de elementen in een reeks in oplopende volgorde volgens een sleutel.
type: docs
weight: 27
url: /nl/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) methode

Voert een nadere sortering uit van de elementen in een reeks in oplopende volgorde volgens een sleutel.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Key | Het type van de sleutel dat wordt geretourneerd door keySelector. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Een functie om een sleutel uit elk element te extraheren. |

### Retourwaarde

[System::Linq::IOrderedEnumerable](../) waarvan de elementen gesorteerd zijn volgens een sleutel.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) methode

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOrderedEnumerable](../)
* Klasse [Func](../../../system/func/)
* Naamruimte [System::Linq](../../)
* Library [Aspose.Slides](../../../)