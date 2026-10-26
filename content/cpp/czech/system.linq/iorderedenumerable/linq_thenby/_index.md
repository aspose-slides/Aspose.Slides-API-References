---
title: LINQ_ThenBy()
second_title: Aspose.Slides pro C++ API referenční příručka
description: Provádí následné řazení prvků v sekvenci vzestupně podle klíče.
type: docs
weight: 27
url: /cs/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) metoda

Provádí následné řazení prvků v sekvenci vzestupně podle klíče.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Key | Typ klíče vráceného funkcí keySelector. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Funkce pro získání klíče z každého prvku. |

### Návratová hodnota

[System::Linq::IOrderedEnumerable](../) jejichž prvky jsou seřazeny podle klíče.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) metoda

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOrderedEnumerable](../)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Linq](../../)
* Knihovna [Aspose.Slides](../../../)