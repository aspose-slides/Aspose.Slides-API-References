---
title: begin()
second_title: Aspose.Slides C++ API referencia
description: Elérő a begin() metódushoz egy alapszintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializált típus, amely rendelkezik begin() metódussal.
type: docs
weight: 378
url: /hu/system/smartptr/begin/
---
## SmartPtr::begin() metódus


Elérő a(z) [begin()](./) metódushoz egy alapszintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializált típus, amely rendelkezik [begin()](./) metódussal.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Visszatérési érték

iterator a gyűjtemény elejéhez

## SmartPtr::begin() const metódus


Elérő a(z) [begin()](./) metódushoz egy alapszintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializált típus, amely rendelkezik [begin()](./) metódussal.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Visszatérési érték

iterator a gyűjtemény elejéhez

## Lásd még

* Osztály [SmartPtr](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)