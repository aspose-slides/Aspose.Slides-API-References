---
title: begin()
second_title: Aspose.Slides pro C++ API Reference
description: Přístupový prvek pro metodu begin() podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ typ specializace s metodou begin().
type: docs
weight: 378
url: /cs/system/smartptr/begin/
---
## SmartPtr::begin() metoda


Přístupový prvek pro metodu [begin()](./) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ typ specializace s metodou [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Návratová hodnota

iterátor na začátek kolekce

## SmartPtr::begin() const metoda


Přístupový prvek pro metodu [begin()](./) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ typ specializace s metodou [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Návratová hodnota

iterátor na začátek kolekce

## Viz také

* třída [SmartPtr](../)
* jmenný prostor [System](../../)
* knihovna [Aspose.Slides](../../../)