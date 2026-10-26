---
title: ConstrainedCopy()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin rentang elemen dari System.Array dimulai pada sumber yang ditentukan.
type: docs
weight: 716
url: /id/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metode

Menyalin rentang elemen dari sebuah [System.Array](../) yang dimulai pada sumber yang ditentukan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| srcIndex | **int64_t** | [Index](../../index/) dalam array sumber yang menunjuk awal rentang item yang akan disalin |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) dalam array tujuan untuk memulai penyisipan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Catatan

IMPLEMENTASI MENTAH SEMENTARA TANPA APAPUN UNDONES!

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [Array](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)