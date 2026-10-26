---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek Nullable yang ditentukan.
type: docs
weight: 131
url: /id/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metode

Menentukan apakah nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe dasar dari objek [Nullable](../) untuk dibandingkan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | Referensi konstan ke objek [Nullable](../) untuk dibandingkan |

### Nilai Kembalian

True jika nilai yang diwakili oleh objek saat ini sama dengan nilai yang diwakili oleh objek [Nullable](../) yang ditentukan, lainnya - false

## Lihat Juga

* Kelas [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)