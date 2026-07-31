---
title: BothArrayOrList
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah kedua argumen tipe berupa array atau list. Jika ya, anggota value diatur ke true, jika tidak diatur ke false.
type: docs
weight: 131
url: /id/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Memeriksa apakah kedua argumen tipe berupa array atau list. Jika ya, anggota value diatur ke true, jika tidak diatur ke false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Lihat Juga

* Ruang Nama [System::TestPredicates::TypeTraits](../)
* Pustaka [Aspose.Slides](../../)