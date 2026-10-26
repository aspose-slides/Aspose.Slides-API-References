---
title: ImplementsInterface< T, IComparable< T > >
second_title: Referensi API Aspose.Slides untuk C++
description: Predikat templat yang memeriksa apakah objek yang dibungkus harus mengimplementasikan antarmuka IComparable dengan sendirinya.
type: docs
weight: 53
url: /id/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct

Predikat templat yang memeriksa apakah objek yang dibungkus harus mengimplementasikan antarmuka [IComparable](../../system/icomparable/) dengan sendirinya.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Lihat Juga

* Ruang Nama [System::BoxedValueDetail](../)
* Perpustakaan [Aspose.Slides](../../)