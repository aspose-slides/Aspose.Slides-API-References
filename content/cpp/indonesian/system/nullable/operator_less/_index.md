---
title: operator<()
second_title: Referensi API Aspose.Slides untuk C++
description: Selalu mengembalikan false.
type: docs
weight: 170
url: /id/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const metode

Selalu mengembalikan false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const metode

Menentukan apakah nilai yang diwakili oleh objek saat ini kurang dari nilai yang ditentukan dengan menerapkan [operator<()](./) pada nilai-nilai ini.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang akan dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke nilai yang akan dibandingkan |

### Nilai Kembalian

True if the value represented by the current object is less than the specified value, otherwise - false

## Nullable::operator<(const Nullable\<T1\>\&) const metode

Menentukan apakah nilai yang diwakili oleh objek saat ini kurang dari nilai yang diwakili oleh objek [Nullable](../) yang ditentukan dengan menerapkan [operator<()](./) pada nilai-nilai ini.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Jenis dasar dari objek [Nullable](../) untuk dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) untuk dibandingkan |

### Nilai Kembalian

True if the value represented by the current object is less than the value represented by the specified [Nullable](../) object, otherwise - false

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)