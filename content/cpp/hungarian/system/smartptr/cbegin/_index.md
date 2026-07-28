---
title: cbegin()
second_title: Aspose.Slides a C++ API Referenciája
description: Az alaptároló gyűjtemény cbegin() metódusához tartozó hozzáférő. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely cbegin() metódussal rendelkezik.
type: docs
weight: 404
url: /hu/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metódus


Hozzáférő a [cbegin()](./) metódushoz egy alaptároló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [cbegin()](./) metódussal rendelkezik.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### Visszatérési érték

iterátor a gyűjtemény elejére

## Lásd még

* Osztály [SmartPtr](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)