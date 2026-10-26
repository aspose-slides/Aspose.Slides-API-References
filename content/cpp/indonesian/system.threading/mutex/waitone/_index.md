---
title: WaitOne()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengunci mutex. Melakukan penantian tak terbatas jika diperlukan.
type: docs
weight: 53
url: /id/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metode

Mengunci mutex. Melakukan penantian tak terbatas jika diperlukan.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Nilai Kembali

Selalu mengembalikan true karena tidak mengembalikan hingga mutex terkunci.

## Mutex::WaitOne(int) metode

Mengunci mutex. Melakukan penantian jika diperlukan.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsTimeout | int | Batas waktu penantian dalam milidetik. |

### Nilai Kembali

Mengembalikan true jika mutex terkunci atau false jika batas waktu terlampaui.

## Mutex::WaitOne(TimeSpan) metode

Mengunci mutex. Melakukan penantian jika diperlukan.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Sebuah [System::TimeSpan](../../../system/timespan/) yang merepresentasikan jumlah milidetik untuk menunggu, atau sebuah [System::TimeSpan](../../../system/timespan/) yang merepresentasikan -1 milidetik untuk menunggu tanpa batas. |

### Nilai Kembali

Mengembalikan true jika mutex terkunci atau false jika batas waktu terlampaui.

## Lihat Juga

* Kelas [Mutex](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Ruang Nama [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)