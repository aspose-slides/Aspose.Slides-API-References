---
title: Coalesce()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi terjemahan operator '??' untuk tipe yang tidak dapat bernilai null.
type: docs
weight: 170
url: /id/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metode


Implementasi terjemahan operator '??' untuk tipe yang tidak dapat bernilai null.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T0 | Tipe nilai LHS. |
| T1 | Tipe lambda yang membungkus ekspresi RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T0 | Nilai LHS. |
| func | T1 | Ekspresi RHS. |

### Nilai Kembali

Jika nilai LHS tidak null, mengembalikan LHS, jika tidak menghitung ekspresi RHS dan mengembalikan hasilnya.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metode


Implementasi terjemahan operator '??' untuk tipe yang dapat bernilai null.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T0 | Tipe nilai LHS. |
| T1 | Tipe lambda yang membungkus ekspresi RHS. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Nilai LHS. |
| func | T1 | Ekspresi RHS. |

### Nilai Kembali

Jika nilai LHS tidak null, mengembalikan LHS, jika tidak menghitung ekspresi RHS dan mengembalikan hasilnya.

## Lihat Juga

* Kelas [ObjectExt](../)
* Kelas [Nullable](../../nullable/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)