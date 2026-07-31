---
title: DynamicCastArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan casting elemen dari array yang ditentukan ke tipe yang berbeda.
type: docs
weight: 2991
url: /id/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) fungsi

Melakukan casting elemen dari array yang ditentukan ke tipe yang berbeda.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| To | Tipe yang akan digunakan untuk melakukan cast pada elemen array yang ditentukan |
| From | Tipe elemen dari array yang elemen-elemennya akan di-cast |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Pointer bersama ke array yang berisi elemen-elemen yang akan di-cast |

### Nilai Kembali

Pointer ke array baru yang berisi elemen dengan tipe **To** yang setara dengan elemen-elemen **from**

Tidak Digunakan
:   Ditambahkan untuk kompatibilitas mundur. Gunakan ExplicitCast sebagai gantinya.

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Kelas [Array](../array/)
* Namespace [System](../)
* Pustaka [Aspose.Slides](../../)