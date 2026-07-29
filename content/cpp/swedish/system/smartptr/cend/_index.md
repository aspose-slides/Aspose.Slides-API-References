---
title: cend()
second_title: Aspose.Slides för C++ API-referens
description: Åtkomstfunktion för cend()-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med cend()-metoden.
type: docs
weight: 417
url: /sv/system/smartptr/cend/
---
## SmartPtr::cend() const metod


Åtkomstfunktion för [cend()](./)-metoden i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiseringstyp med [cend()](./)-metoden.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```


### Returvärde

iterator till slutet av samlingen

## Se också

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)