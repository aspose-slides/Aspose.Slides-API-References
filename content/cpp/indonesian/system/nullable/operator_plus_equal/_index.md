---
title: operator+=()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengatur ulang objek saat ini sehingga mewakili nilai null.
type: docs
weight: 235
url: /id/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metode

Mengatur ulang objek saat ini sehingga mewakili nilai null.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Nilai Kembalian

Salinan dari objek itu

## Nullable::operator+=(const T1\&) metode

Menerapkan [operator+=()](./) pada nilai yang diwakili oleh objek saat ini dengan menggunakan nilai yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Parameter Templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang digunakan sebagai nilai sisi kanan dari [operator+=()](./) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke nilai yang digunakan sebagai nilai sisi kanan dari [operator+=()](./) yang diterapkan pada nilai yang diwakili oleh objek saat ini. |

### Nilai Kembalian

Referensi ke objek itu

## Nullable::operator+=(const Nullable\<T1\>\&) metode

Menerapkan [operator+=()](./) pada nilai yang diwakili oleh objek saat ini dengan menggunakan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan sebagai argumen sisi kanan.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Parameter Templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) yang nilai yang diwakilinya digunakan sebagai argumen sisi kanan dari [operator+=()](./) |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) yang nilai yang diwakilinya digunakan sebagai argumen sisi kanan dari [operator+=()](./) yang diterapkan pada nilai yang diwakili oleh objek saat ini. |

### Nilai Kembalian

Referensi ke objek itu

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)