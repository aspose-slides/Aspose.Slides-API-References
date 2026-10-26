---
title: cbegin()
second_title: Aspose.Slides för C++ API-referens
description: Åtkomstfunktion för cbegin()-metod i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiserad typ med cbegin()-metod.
type: docs
weight: 404
url: /sv/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metod

Åtkomstfunktion för [cbegin()](./)-metod i en underliggande samling. Kompileras endast om SmartPtr_ är en specialiserad typ med [cbegin()](./)-metod.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Returvärde

iterator till början av samlingen

## Se även

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)