---
title: end()
second_title: Aspose.Slides C++ API referencia
description: Az alapszintű gyűjtemény end() metódusához tartozó hozzáférő. Csak akkor fordul le, ha a SmartPtr_ specializációs típus az end() metódussal.
type: docs
weight: 391
url: /hu/system/smartptr/end/
---
## SmartPtr::end() metódus

Az [end()](./) metódus hozzáférője egy alapszintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [end()](./) metódussal.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### Visszatérési érték

iterátor a gyűjtemény végére

## SmartPtr::end() const metódus

Az [end()](./) metódus hozzáférője egy alapszintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [end()](./) metódussal.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### Visszatérési érték

iterátor a gyűjtemény végére

## Lásd még

* Osztály [SmartPtr](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)