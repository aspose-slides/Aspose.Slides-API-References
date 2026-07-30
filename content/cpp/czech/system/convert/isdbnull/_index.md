---
title: IsDBNull()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: NEIMPLEMENTOVÁNO.
type: docs
weight: 14
url: /cs/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) metoda


NEIMPLEMENTOVÁNO.

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```


## Convert::IsDBNull(const SharedPtr\<T\>\&) metoda


NEIMPLEMENTOVÁNO Falešná implementace, kontroluje, zda je hodnota nullptr.

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## Viz také

* Definice typu [SharedPtr](../../sharedptr/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [Convert](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)