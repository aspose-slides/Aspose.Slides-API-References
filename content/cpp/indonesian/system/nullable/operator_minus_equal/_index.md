---
title: operator-=()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah instance dari kelas Nullable yang mewakili nilai null.
type: docs
weight: 248
url: /id/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metode

Mengembalikan sebuah instance dari kelas [Nullable](../) yang mewakili nilai null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metode

Menerapkan [operator-=()](./) ke nilai yang diwakili oleh objek saat ini dengan menggunakan nilai yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang digunakan sebagai nilai sisi kanan dari [operator-=()](./) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke nilai yang digunakan sebagai nilai sisi kanan dari [operator-=()](./) yang diterapkan pada nilai yang diwakili oleh objek saat ini. |

### Nilai Kembalian

Referensi ke diri sendiri

## Nullable::operator-=(const Nullable\<T1\>\&) metode

Menerapkan [operator-=()](./) ke nilai yang diwakili oleh objek saat ini dengan menggunakan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) yang nilai yang diwakili olehnya digunakan sebagai argumen sisi kanan dari [operator-=()](./) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) yang nilai yang diwakili olehnya digunakan sebagai argumen sisi kanan dari [operator-=()](./) yang diterapkan pada nilai yang diwakili oleh objek saat ini. |

### Nilai Kembalian

Referensi ke diri sendiri

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)