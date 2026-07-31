---
title: operator|=()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerapkan operator|=() ke nilai yang direpresentasikan oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan.
type: docs
weight: 261
url: /id/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) metode

Menerapkan [operator|=()](./) ke nilai yang direpresentasikan oleh objek saat ini menggunakan nilai yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Parameter Templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Parameter templat untuk membuat SFINAE berfungsi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | **bool** | Nilai boolean yang digunakan sebagai nilai sisi kanan dari [operator|=()](./) yang diterapkan ke nilai yang direpresentasikan oleh objek saat ini. |

### Nilai Kembali

Referensi ke diri sendiri.

## Lihat Juga

* Kelas [Nullable](../)
* Ruang nama [System](../../)
* Pustaka [Aspose.Slides](../../../)