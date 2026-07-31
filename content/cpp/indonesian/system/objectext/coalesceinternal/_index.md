---
title: CoalesceInternal()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi terjemahan operator '??' untuk tipe yang tidak dapat bernilai null. Overload untuk kasus jika RT2 dapat dikonversi ke RT1.
type: docs
weight: 157
url: /id/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metode

Implementasi terjemahan operator '??' untuk tipe yang tidak dapat bernilai null. Overload untuk kasus jika RT2 dapat dikonversi ke RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T0 | tipe nilai LHS. |
| T1 | Tipe lambda yang membungkus ekspresi RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | RT1 | nilai LHS. |
| func | F | ekspresi RHS. |

### Nilai Kembalian

Jika nilai LHS tidak null, mengembalikan LHS, jika tidak menghitung ekspresi RHS dan mengembalikan hasilnya.

## Lihat Juga

* Kelas [ObjectExt](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)