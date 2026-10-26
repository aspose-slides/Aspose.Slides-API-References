---
title: operator>=()
second_title: Referensi API Aspose.Slides untuk C++
description: Selalu mengembalikan false.
type: docs
weight: 183
url: /id/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const metode


Selalu mengembalikan false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Nilai Kembalian

Selalu - false

## Nullable::operator>=(const T1\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek yang ditentukan dengan menerapkan [operator>=()](./) pada nilai-nilai ini.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari nilai untuk membandingkan nilai yang diwakili oleh objek saat ini dengan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke objek untuk membandingkan objek saat ini dengan |

### Nilai Kembalian

True jika nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek yang ditentukan, selainnya - false

## Nullable::operator>=(const Nullable\<T1\>\&) const metode


Menentukan apakah nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan dengan menerapkan [operator>=()](./) pada nilai-nilai ini.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) untuk dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Referensi konstan ke objek [Nullable](../) untuk dibandingkan |

### Nilai Kembalian

True jika nilai yang diwakili oleh objek saat ini lebih besar atau sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan, selainnya - false

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)