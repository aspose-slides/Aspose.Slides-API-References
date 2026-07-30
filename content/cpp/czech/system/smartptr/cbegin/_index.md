---
title: cbegin()
second_title: Aspose.Slides pro C++ – Referenční příručka API
description: Přístupová metoda k metodě cbegin() podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ typ specializace s metodou cbegin().
type: docs
weight: 404
url: /cs/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metoda

Přístupová metoda k metodě [cbegin()](./) podkladové kolekce. Kompiluje se pouze, pokud je SmartPtr_ typ specializace s metodou [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Návratová hodnota

iterátor na začátek kolekce

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)