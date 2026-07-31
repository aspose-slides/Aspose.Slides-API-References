---
title: Wait()
second_title: Referensi API Aspose.Slides untuk C++
description: Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci. Jika interval batas waktu yang ditentukan berakhir, thread masuk ke antrian siap. Secara opsional keluar dari domain sinkronisasi untuk konteks tersinkronisasi sebelum menunggu dan memperoleh kembali domain setelahnya. Tidak diimplementasikan.
type: docs
weight: 53
url: /id/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) metode

Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci. Jika interval batas waktu yang ditentukan berakhir, thread masuk ke antrian siap. Secara opsional keluar dari domain sinkronisasi untuk konteks tersinkronisasi sebelum menunggu dan memperoleh kembali domain setelahnya. Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) metode

Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci. Jika interval batas waktu yang ditentukan berakhir, thread masuk ke antrian siap. Secara opsional keluar dari domain sinkronisasi untuk konteks tersinkronisasi sebelum menunggu dan memperoleh kembali domain setelahnya. Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) metode

Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci. Jika interval batas waktu yang ditentukan berakhir, thread masuk ke antrian siap. Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) metode

Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci. Jika interval batas waktu yang ditentukan berakhir, thread masuk ke antrian siap. Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) metode

Melepaskan kunci pada sebuah objek dan memblokir thread saat ini sampai kembali memperoleh kunci Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Monitor](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Ruang Nama [System::Threading](../../)
* Library [Aspose.Slides](../../../)