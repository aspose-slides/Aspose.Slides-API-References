---
title: end()
second_title: Aspose.Slides för C++ API-referens
description: Åtkomstfunktion för end() metod i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med end() metod.
type: docs
weight: 391
url: /sv/system/smartptr/end/
---
## SmartPtr::end() metod


Åtkomstfunktion för [end()](./) metod för en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [end()](./) metod.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Returvärde

iterator to the end of collection

## SmartPtr::end() const metod


Åtkomstfunktion för [end()](./) metod för en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [end()](./) metod.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Returvärde

iterator to the end of collection

## Se också

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)