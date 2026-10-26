---
title: LINQ_GroupBy()
second_title: Aspose.Slides för C++ API-referens
description: Grupperar elementen i en sekvens.
type: docs
weight: 287
url: /sv/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metod

Grupperar elementen i en sekvens.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Key | Typen av nyckeln som returneras av keyPredicate |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | En funktion för att extrahera nyckeln för varje element. |

### Returvärde

En [IEnumerable](../) som innehåller en sekvens av objekt och en nyckel

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metod

Grupperar elementen i en sekvens.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Key | Typen av nyckeln som returneras av keyPredicate |
| Element | Typen av elementet som returneras av elementSelector |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | En funktion för att extrahera nyckeln för varje element. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | En funktion för att extrahera värde-nyckeln för varje element. |

### Returvärde

En [IEnumerable](../) som innehåller en sekvens av objekt och en nyckel

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metod




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metod




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)