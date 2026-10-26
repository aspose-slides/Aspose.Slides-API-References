---
title: LINQ_GroupBy()
second_title: Aspose.Slides pro C++ API Reference
description: Skupinuje prvky sekvence.
type: docs
weight: 287
url: /cs/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metoda

Skupinuje prvky sekvence.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Key | Typ klíče vráceného funkcí keyPredicate |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Funkce pro získání klíče pro každý prvek. |

### Návratová hodnota

Instanci [IEnumerable](../), která obsahuje sekvenci objektů a klíč

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metoda

Skupinuje prvky sekvence.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Key | Typ klíče vráceného funkcí keyPredicate |
| Element | Typ prvku vráceného funkcí elementSelector |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Funkce pro získání klíče pro každý prvek. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Funkce pro získání hodnoty klíče pro každý prvek. |

### Návratová hodnota

Instanci [IEnumerable](../), která obsahuje sekvenci objektů a klíč

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metoda



```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metoda



```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IEnumerable](../)
* Třída [IGrouping](../../../system.linq/igrouping/)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)