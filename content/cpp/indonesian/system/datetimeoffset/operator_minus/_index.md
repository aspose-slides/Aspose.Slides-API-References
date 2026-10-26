---
title: operator-()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah instance baru dari kelas DateTimeOffset yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini.
type: docs
weight: 521
url: /id/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const metode

Mengembalikan sebuah instance baru dari kelas [DateTimeOffset](../) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan rentang waktu yang ditentukan dari nilai yang diwakili oleh objek saat ini.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Interval waktu yang akan dikurangkan |

### Nilai Kembali

Sebuah instance baru dari kelas [DateTimeOffset](../) yang mewakili nilai tanggal dan waktu yang merupakan hasil pengurangan **value** dari nilai yang diwakili oleh objek saat ini.

## DateTimeOffset::operator-(const DateTimeOffset\&) const metode

Mengembalikan sebuah instance dari kelas [TimeSpan](../../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan objek yang ditentukan.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Sebuah instance dari kelas [DateTime](../../datetime/) yang menandai salah satu ujung interval yang akan dihitung |

### Nilai Kembali

Sebuah instance dari kelas [TimeSpan](../../timespan/) yang mewakili interval waktu antara nilai tanggal dan waktu yang diwakili oleh objek saat ini dan **other**.

## Lihat Juga

* Kelas [DateTimeOffset](../)
* Kelas [TimeSpan](../../timespan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)