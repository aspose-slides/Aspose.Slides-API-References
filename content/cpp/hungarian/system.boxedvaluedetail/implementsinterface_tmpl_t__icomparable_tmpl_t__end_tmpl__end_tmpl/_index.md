---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides C++ API hivatkozás
description: Sablon előfeltétel, amely ellenőrzi, hogy a dobozolt objektumnak saját maga kell-e megvalósítania az IComparable interfészt.
type: docs
weight: 53
url: /hu/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Sablon előfeltétel, amely ellenőrzi, hogy a dobozolt objektumnak saját maga kell-e megvalósítania a [IComparable](../../system/icomparable/) interfészt.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Lásd még

* Névtér [System::BoxedValueDetail](../)
* Könyvtár [Aspose.Slides](../../)