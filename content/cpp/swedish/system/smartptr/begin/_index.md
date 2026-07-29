---
title: begin()
second_title: Aspose.Slides för C++ API-referens
description: Åtkomstfunktion för begin() metod i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med begin() metod.
type: docs
weight: 378
url: /sv/system/smartptr/begin/
---
## SmartPtr::begin() metod


Åtkomstfunktion för [begin()](./) metod för en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [begin()](./) metod.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Returvärde

iterator till början av samlingen

## SmartPtr::begin() const metod


Åtkomstfunktion för [begin()](./) metod för en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [begin()](./) metod.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Returvärde

iterator till början av samlingen

## Se även

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)