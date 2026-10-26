---
title: WaitOne()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu handle untuk dipicu selama periode tak terbatas.
type: docs
weight: 27
url: /id/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metode

Menunggu handle untuk dipicu selama periode tak terbatas.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Nilai Kembali

Selalu mengembalikan true karena tidak ada batas waktu terjadi.

## WaitHandle::WaitOne(int) metode

Menunggu handle untuk dipicu.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) untuk menunggu, dalam milidetik; -1 berarti menunggu tak terbatas, 0 berarti periksa-dan-kembali, nilai positif adalah batas waktu. |

### Nilai Kembali

True jika handle dipicu, false jika batas waktu terlampaui.

## WaitHandle::WaitOne(TimeSpan) metode

Menunggu handle untuk dipicu.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Sebuah [System::TimeSpan](../../../system/timespan/) yang mewakili jumlah milidetik untuk menunggu, atau sebuah [System::TimeSpan](../../../system/timespan/) yang mewakili -1 milidetik untuk menunggu tanpa batas. |

### Nilai Kembali

True jika handle dipicu, false jika batas waktu terlampaui.

## WaitHandle::WaitOne(int, bool) metode

Menunggu handle untuk dipicu.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) untuk menunggu, dalam milidetik; -1 berarti menunggu tak terbatas, 0 berarti periksa-dan-kembali, nilai positif adalah batas waktu. |
| exitContext | **bool** | Jika true, penantian harus melepaskan kunci pada handle sebelum menunggu. |

### Nilai Kembali

True jika handle dipicu, false jika batas waktu terlampaui.

## Lihat Juga

* Kelas [WaitHandle](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)