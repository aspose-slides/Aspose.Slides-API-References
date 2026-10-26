---
title: LINQ_GroupBy()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Grupuje elementy sekwencji.
type: docs
weight: 287
url: /pl/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metoda


Grupuje elementy sekwencji.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Key | Typ klucza zwracanego przez keyPredicate |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Funkcja ekstrakcji klucza dla każdego elementu. |

### Wartość zwracana

Obiekt [IEnumerable](../) zawierający sekwencję obiektów i klucz

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metoda


Grupuje elementy sekwencji.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Key | Typ klucza zwracanego przez keyPredicate |
| Element | Typ elementu zwracanego przez elementSelector |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Funkcja ekstrakcji klucza dla każdego elementu. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Funkcja ekstrakcji wartości klucza dla każdego elementu. |

### Wartość zwracana

Obiekt [IEnumerable](../) zawierający sekwencję obiektów i klucz

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metoda




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metoda




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IEnumerable](../)
* Klasa [IGrouping](../../../system.linq/igrouping/)
* Klasa [Func](../../../system/func/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)