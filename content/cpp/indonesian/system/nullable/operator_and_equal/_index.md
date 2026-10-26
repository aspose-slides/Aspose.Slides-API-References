---
title: operator&=()
second_title: Aspose.Slides untuk Referensi API C++
description: Menerapkan operator&=() ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan.
type: docs
weight: 274
url: /id/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metode


Menerapkan [operator&=()](./) ke nilai yang diwakili oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Parameter templat untuk membuat SFINAE berfungsi. |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| other | **bool** | Nilai boolean yang digunakan sebagai nilai sisi kanan dari [operator&=()](./) yang diterapkan pada nilai yang diwakili oleh objek saat ini. |

### Nilai Kembali

Referensi ke diri sendiri.

## Lihat Juga

* Kelas [Nullable](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)