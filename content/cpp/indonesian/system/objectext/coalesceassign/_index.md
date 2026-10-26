---
title: CoalesceAssign()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi terjemahan operator '??='.
type: docs
weight: 183
url: /id/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metode


Implementasi terjemahan operator '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T0 | Tipe nilai LHS. |
| T1 | Tipe lambda yang mengenkapsulasi ekspresi RHS. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0\& | nilai LHS. |
| func | T1 | ekspresi RHS. |

### Nilai Kembalian

Jika nilai LHS tidak null, mengembalikan LHS, jika tidak menghitung ekspresi RHS dan mengembalikan hasil.

## Lihat Juga

* Kelas [ObjectExt](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)