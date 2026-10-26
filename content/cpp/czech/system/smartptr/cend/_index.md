---
title: cend()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přístupový prvek pro metodu cend() podkladové kolekce. Kompiluje pouze pokud je SmartPtr_ specializační typ s metodou cend().
type: docs
weight: 417
url: /cs/system/smartptr/cend/
---
## SmartPtr::cend() const metoda


Přístupový prvek pro [cend()](./) metodu podkladové kolekce. Kompiluje pouze pokud SmartPtr_ je specializační typ s [cend()](./) metodou.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```


### Návratová hodnota

iterátor na konec kolekce

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)