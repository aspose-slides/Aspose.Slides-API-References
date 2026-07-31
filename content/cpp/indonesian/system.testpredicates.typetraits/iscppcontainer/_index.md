---
title: IsCppContainer
second_title: Referensi API Aspose.Slides untuk C++
description: "Memeriksa apakah tipe tertentu adalah kontainer gaya STL. Untuk melakukannya, memeriksa keberadaan tipe anggota iterator dan const_iterator. Jika keduanya ada, mewarisi std::true_type, jika tidak mewarisi std::false_type."
type: docs
weight: 40
url: /id/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Memeriksa apakah tipe tertentu adalah kontainer gaya STL. Untuk melakukannya, memeriksa keberadaan tipe anggota iterator dan const_iterator. Jika keduanya ada, mewarisi std::true_type, jika tidak mewarisi std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang akan diperiksa. |
| Enable | Argumen formal agar SFINAE berfungsi. |

## Lihat Juga

* Namespace [System::TestPredicates::TypeTraits](../)
* Perpustakaan [Aspose.Slides](../../)