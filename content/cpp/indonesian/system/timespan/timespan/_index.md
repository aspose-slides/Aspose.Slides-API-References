---
title: TimeSpan()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek TimeSpan yang merepresentasikan interval waktu nol.
type: docs
weight: 1
url: /id/system/timespan/timespan/
---
## TimeSpan::TimeSpan() konstruktor


Membuat objek [TimeSpan](../) yang merepresentasikan interval waktu nol.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) konstruktor


Membuat instance dari kelas [TimeSpan](../) yang merepresentasikan interval waktu yang ditentukan.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ticks | **int64_t** | Interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun, diekspresikan sebagai jumlah interval 100-nanodetik. |

## TimeSpan::TimeSpan(int, int, int) konstruktor


Membuat instance dari kelas [TimeSpan](../) yang merepresentasikan interval waktu yang sama dengan jumlah jam, menit, dan detik yang ditentukan.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hours | int | Jumlah jam dalam komponen jam interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| minutes | int | Jumlah menit dalam komponen menit interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| seconds | int | Jumlah detik dalam komponen detik interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |

## TimeSpan::TimeSpan(int, int, int, int, int) konstruktor


Membuat instance dari kelas [TimeSpan](../) yang merepresentasikan interval waktu yang sama dengan jumlah jam, menit, detik, dan milidetik yang ditentukan.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| days | int | Jumlah hari dalam komponen hari interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| hours | int | Jumlah jam dalam komponen jam interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| minutes | int | Jumlah menit dalam komponen menit interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| seconds | int | Jumlah detik dalam komponen detik interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |
| milliseconds | int | Jumlah milidetik dalam komponen milidetik interval waktu yang akan direpresentasikan oleh instance yang sedang dibangun |

## TimeSpan::TimeSpan(const TimeSpan\&) konstruktor


Membuat objek [TimeSpan](../) yang merepresentasikan interval waktu yang sama dengan interval waktu yang direpresentasikan oleh objek [TimeSpan](../) yang ditentukan.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Lihat Juga

* Kelas [TimeSpan](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)