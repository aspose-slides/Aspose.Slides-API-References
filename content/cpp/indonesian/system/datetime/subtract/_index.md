---
title: Subtract()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengembalikan sebuah instance baru dari kelas DateTime yang merepresentasikan nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang direpresentasikan oleh objek saat ini.
type: docs
weight: 326
url: /id/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metode

Mengembalikan sebuah instance baru dari kelas [DateTime](../) yang merepresentasikan nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang direpresentasikan oleh objek saat ini.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Sebuah interval waktu yang akan dikurangkan |

### Nilai Kembali

Sebuah instance baru dari kelas [DateTime](../) yang merepresentasikan nilai tanggal dan waktu yang merupakan hasil pengurangan **duration** dari nilai yang direpresentasikan oleh objek saat ini.

## DateTime::Subtract(DateTime) const metode

Mengembalikan sebuah instance dari kelas [TimeSpan](../../timespan/) yang merepresentasikan interval waktu antara nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini dan objek yang ditentukan.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DateTime](../) | Sebuah instance dari kelas [DateTime](../) yang menandai salah satu ujung interval yang akan dihitung |

### Nilai Kembali

Sebuah instance dari kelas [TimeSpan](../../timespan/) yang merepresentasikan interval waktu antara nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini dan **value**.

## Lihat Juga

* Kelas [DateTime](../)
* Kelas [TimeSpan](../../timespan/)
* RuangNama [System](../../)
* Library [Aspose.Slides](../../../)