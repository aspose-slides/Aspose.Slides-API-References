---
title: LINQ_GroupBy()
second_title: Aspose.Slides für C++ API-Referenz
description: Gruppiert die Elemente einer Sequenz.
type: docs
weight: 287
url: /de/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) Methode

Gruppiert die Elemente einer Sequenz.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Key | Der Typ des Schlüssels, der von keyPredicate zurückgegeben wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Eine Funktion, die den Schlüssel für jedes Element extrahiert. |

### Rückgabewert

Ein [IEnumerable](../) der eine Sequenz von Objekten und einen Schlüssel enthält

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) Methode

Gruppiert die Elemente einer Sequenz.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Key | Der Typ des Schlüssels, der von keyPredicate zurückgegeben wird |
| Element | Der Typ des Elements, das von elementSelector zurückgegeben wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Eine Funktion, die den Schlüssel für jedes Element extrahiert. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Eine Funktion, die den Schlüsselwert für jedes Element extrahiert. |

### Rückgabewert

Ein [IEnumerable](../) der eine Sequenz von Objekten und einen Schlüssel enthält

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) Methode




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) Methode




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../)
* Klasse [IGrouping](../../../system.linq/igrouping/)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)