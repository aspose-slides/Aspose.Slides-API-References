---
title: LINQ_GroupBy()
second_title: Aspose.Slides voor C++ API-referentie
description: Groepeert de elementen van een reeks.
type: docs
weight: 287
url: /nl/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) methode


Groepeert de elementen van een reeks.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Key | Het type van de sleutel die door keyPredicate wordt geretourneerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Een functie om de sleutel voor elk element te extraheren. |

### Retourwaarde

Een [IEnumerable](../) die een reeks objecten en een sleutel bevat

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) methode


Groepeert de elementen van een reeks.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Key | Het type van de sleutel die door keyPredicate wordt geretourneerd |
| Element | Het type van het element dat door elementSelector wordt geretourneerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Een functie om de sleutel voor elk element te extraheren. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Een functie om de waardesleutel voor elk element te extraheren. |

### Retourwaarde

Een [IEnumerable](../) die een reeks objecten en een sleutel bevat

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) methode




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) methode




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../)
* Klasse [IGrouping](../../../system.linq/igrouping/)
* Klasse [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)