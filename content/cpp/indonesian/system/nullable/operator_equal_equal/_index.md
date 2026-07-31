---
title: operator==()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah nilai yang diwakili oleh objek saat ini null.
type: docs
weight: 118
url: /id/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini bernilai null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Nilai Kembali

True jika nilai yang diwakili oleh objek saat ini null, jika tidak - false

## Nullable::operator==(const T1\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang ditentukan.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai yang akan dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke nilai yang akan dibandingkan |

### Nilai Kembali

True jika nilai yang diwakili oleh objek saat ini sama dengan nilai yang ditentukan, jika tidak - false

## Nullable::operator==(const Nullable\<T1\>\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) untuk dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) untuk dibandingkan |

### Nilai Kembali

True jika nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan, jika tidak - false

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang nama [System](../../)
* Pustaka [Aspose.Slides](../../../)