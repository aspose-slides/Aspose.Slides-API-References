---
title: operator-()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah instansi baru dari kelas DateTime yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini.
type: docs
weight: 651
url: /id/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metode

Mengembalikan sebuah instansi baru dari kelas [DateTime](../) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Interval waktu yang akan dikurangkan |

### Nilai Kembalian

Instansi baru dari kelas [DateTime](../) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan **value** dari nilai yang diwakili oleh objek saat ini.

## DateTime::operator-(DateTime) const metode

Mengembalikan sebuah instansi dari kelas [TimeSpan](../../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan objek yang ditentukan.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DateTime](../) | Sebuah instansi dari kelas [DateTime](../) yang menandai satu ujung interval yang akan dihitung |

### Nilai Kembalian

Instansi dari kelas [TimeSpan](../../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan **value**.

## Lihat Juga

* Kelas [DateTime](../)
* Kelas [TimeSpan](../../timespan/)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)