---
title: BinarySearch()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een binaire zoekopdracht uit in de gesorteerde array.
type: docs
weight: 612
url: /nl/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) methode

Voert een binaire zoekopdracht uit in de gesorteerde array.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Gesorteerde array waarin gezocht moet worden |
| item | const T\& | Een item om te zoeken |

### Retourwaarde

[Index](../../index/) van het gezochte item als er één wordt gevonden, anders een negatief geheel getal dat de bitwise complement is van de index van het volgende item dat groter is dan het gezochte item of, als er geen groter item is, de bitwise complement van het aantal elementen in de array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) methode

NIET GEREALISEERD.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../)
* Klasse [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)