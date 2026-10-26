---
title: end()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přístupový prvek pro metodu end() podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ typ specializace s metodou end().
type: docs
weight: 391
url: /cs/system/smartptr/end/
---
## SmartPtr::end() metoda


Přístupový prvek pro metodu [end()](./) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ typ specializace s metodou [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Návratová hodnota

iterátor na konec kolekce

## SmartPtr::end() const metoda


Přístupový prvek pro metodu [end()](./) podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ typ specializace s metodou [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Návratová hodnota

iterátor na konec kolekce

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)