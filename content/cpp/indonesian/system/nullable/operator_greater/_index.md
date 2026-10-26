---
title: operator>()
second_title: Referensi API Aspose.Slides untuk C++
description: Selalu mengembalikan false.
type: docs
weight: 157
url: /id/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const metode


Selalu mengembalikan false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar daripada nilai yang ditentukan dengan menerapkan [operator>()](./) pada nilai-nilai tersebut.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang akan dibandingkan dengan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke nilai yang akan dibandingkan dengan |

### Nilai Kembalian

True jika nilai yang diwakili oleh objek saat ini lebih besar daripada nilai yang ditentukan, jika tidak - false

## Nullable::operator>(const Nullable\<T1\>\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar daripada nilai yang diwakili oleh objek [Nullable](../) yang ditentukan dengan menerapkan [operator>()](./) pada nilai-nilai tersebut.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) untuk dibandingkan dengan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) untuk dibandingkan dengan |

### Nilai Kembalian

True jika nilai yang diwakili oleh objek saat ini lebih besar daripada nilai yang diwakili oleh objek [Nullable](../) yang ditentukan, jika tidak - false

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)