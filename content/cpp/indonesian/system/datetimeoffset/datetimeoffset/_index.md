---
title: DateTimeOffset()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor default.
type: docs
weight: 1
url: /id/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() konstruktor

Konstruktor default.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Tanggal dan waktu. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ticks | **int64_t** | Jumlah tick. |
| offset | [TimeSpan](../../timespan/) | Offset waktu dari UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Tanggal dan waktu. |
| offset | [TimeSpan](../../timespan/) | Offset waktu dari UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun (1 sampai 9999). |
| month | int | Bulan (1 sampai 12). |
| day | int | Hari (1 sampai jumlah hari dalam bulan). |
| hour | int | Jam (0 sampai 23). |
| minute | int | Menit (0 sampai 59). |
| second | int | Detik (0 sampai 59). |
| offset | [TimeSpan](../../timespan/) | Offset waktu dari UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun (1 sampai 9999). |
| month | int | Bulan (1 sampai 12). |
| day | int | Hari (1 sampai jumlah hari dalam bulan). |
| hour | int | Jam (0 sampai 23). |
| minute | int | Menit (0 sampai 59). |
| second | int | Detik (0 sampai 59). |
| millisecond | int | Milidetik (0 sampai 999). |
| offset | [TimeSpan](../../timespan/) | Offset waktu dari UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun. |
| month | int | Bulan (1 sampai 12). |
| day | int | Hari (1 sampai jumlah hari dalam bulan). |
| hour | int | Jam (0 sampai 23). |
| minute | int | Menit (0 sampai 59). |
| second | int | Detik (0 sampai 59). |
| millisecond | int | Milidetik (0 sampai 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender yang digunakan untuk menginterpretasikan tahun, bulan, dan hari. |
| offset | [TimeSpan](../../timespan/) | Offset waktu dari UTC. |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [DateTimeOffset](../)
* Kelas [DateTime](../../datetime/)
* Kelas [TimeSpan](../../timespan/)
* Kelas [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)