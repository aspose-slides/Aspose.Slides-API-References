---
title: DateTime()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu terkecil yang mungkin yang sama dengan MinValue.
type: docs
weight: 1
url: /id/system/datetime/datetime/
---
## DateTime::DateTime() konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu terkecil yang mungkin yang sama dengan MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, dan hari tertentu.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, dan hari tertentu dalam kalender yang ditentukan.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender yang digunakan untuk menginterpretasikan **year**, **month**, dan **day** yang ditentukan. |

## DateTime::DateTime(int, int, int, int, int, int) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| hour | int | Jam dari **day** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| minute | int | Menit dari **hour** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| second | int | Detik dari **minute** yang akan direpresentasikan oleh instance yang sedang dibangun. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| hour | int | Jam dari **day** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| minute | int | Menit dari **hour** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| second | int | Detik dari **minute** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| kind | [DateTimeKind](../../datetimekind/) | Nilai yang menunjukkan apakah parameter tanggal dan waktu yang diberikan menentukan waktu lokal, waktu UTC, atau tidak keduanya. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, dan detik tertentu dalam kalender yang ditentukan.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| hour | int | Jam dari **day** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| minute | int | Menit dari **hour** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| second | int | Detik dari **minute** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender yang digunakan untuk menginterpretasikan **year**, **month**, dan **day** yang ditentukan. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, detik, dan milidetik tertentu.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| hour | int | Jam dari **day** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| minute | int | Menit dari **hour** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| second | int | Detik dari **minute** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| millisecond | int | Milidetik dari **second** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| kind | [DateTimeKind](../../datetimekind/) | Nilai yang menunjukkan apakah parameter tanggal dan waktu yang diberikan menentukan waktu lokal, waktu UTC, atau tidak keduanya. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai tahun, bulan, hari, jam, menit, detik, dan milidetik tertentu dalam kalender yang ditentukan.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| year | int | Tahun yang akan direpresentasikan oleh instance yang sedang dibangun. |
| month | int | Bulan dari **year** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| day | int | Hari dari **month** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| hour | int | Jam dari **day** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| minute | int | Menit dari **hour** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| second | int | Detik dari **minute** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| millisecond | int | Milidetik dari **second** yang akan direpresentasikan oleh instance yang sedang dibangun. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Nilai yang menunjukkan apakah parameter tanggal dan waktu yang diberikan menentukan waktu lokal, waktu UTC, atau tidak keduanya. |
| calendar | [DateTimeKind](../../datetimekind/) | Kalender yang digunakan untuk menginterpretasikan **year**, **month**, dan **day** yang ditentukan. |

## DateTime::DateTime(int64_t, DateTimeKind) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai sejumlah tick.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ticks | **int64_t** | Jumlah interval 100-ns yang telah berlalu sejak 1 Januari 0001 00:00:00.000 dalam kalender Georgia. |
| kind | [DateTimeKind](../../datetimekind/) | Nilai yang menunjukkan apakah parameter **ticks** menentukan waktu lokal, waktu UTC, atau tidak keduanya. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) konstruktor


Membuat sebuah instance yang merepresentasikan nilai tanggal dan waktu yang ditentukan sebagai sejumlah tick. UNTUK PENGGUNAAN INTERNAL.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ticks | **int64_t** | Jumlah interval 100-ns yang telah berlalu sejak 1 Januari 0001 00:00:00.000 dalam kalender Georgia. |
| kind | [DateTimeKind](../../datetimekind/) | Nilai yang menunjukkan apakah parameter **ticks** menentukan waktu lokal, waktu UTC, atau tidak keduanya. |
| is_ambiguous_local_dst | **bool** | True jika tanggal dan waktu yang ditentukan ambigu dan dapat dipetakan ke banyak waktu UTC. |

## DateTime::DateTime(const DateTime\&) konstruktor


Membuat salinan sebuah instance.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Sebuah instance dari kelas [DateTime](../) untuk menyalin nilai tanggal dan waktu yang direpresentasikan darinya |

## Lihat Juga

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [DateTime](../)
* Kelas [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)