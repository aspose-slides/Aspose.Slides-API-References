---
title: AbstractEqual()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua koleksi dengan tipe yang tidak diketahui.
type: docs
weight: 14
url: /id/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metode


Membandingkan dua koleksi dengan tipe yang tidak diketahui.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen koleksi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Koleksi LHS. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Koleksi RHS. |

### Nilai Kembalian

true jika koleksi cocok (misalnya keduanya null), atau jika ukuran cocok dan elemen cocok, false jika tidak.

## Lihat Juga

* Kelas [ICollection](../../../system.collections.generic/icollection/)
* Struct [TestCompare](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)