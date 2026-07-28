---
title: cend()
second_title: Aspose.Slides C++ API referencia
description: Hozzáférés a cend() metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a cend() metódussal rendelkezik.
type: docs
weight: 417
url: /hu/system/smartptr/cend/
---
## SmartPtr::cend() const metódus

Hozzáférés a [cend()](./) metódusához egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [cend()](./) metódussal rendelkezik.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Visszatérési érték

iterátor a gyűjtemény végére

## Lásd még

* Osztály [SmartPtr](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)