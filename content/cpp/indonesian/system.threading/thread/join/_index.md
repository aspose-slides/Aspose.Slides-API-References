---
title: Join()
second_title: Aspose.Slides untuk Referensi API C++
description: Menggabungkan thread yang dikelola. Melakukan penunggu tak terbatas jika diperlukan.
type: docs
weight: 196
url: /id/system.threading/thread/join/
---
## Thread::Join() metode

Menggabungkan thread yang dikelola. Melakukan penunggu tak terbatas jika diperlukan.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) metode

Menggabungkan thread yang dikelola. Melakukan penunggu terbatas.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsTimeout | int | Batas waktu penunggu dalam milidetik. |

### Nilai Kembalian

True jika thread berhasil digabungkan, false jika batas waktu terlampaui.

## Thread::Join(TimeSpan) metode

Menggabungkan thread yang dikelola. Melakukan penunggu terbatas.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Sebuah [TimeSpan](../../../system/timespan/) yang diatur ke jumlah waktu untuk menunggu thread berhenti. |

### Nilai Kembalian

True jika thread berhasil digabungkan, false jika batas waktu terlampaui.

## Lihat Juga

* Kelas [Thread](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)