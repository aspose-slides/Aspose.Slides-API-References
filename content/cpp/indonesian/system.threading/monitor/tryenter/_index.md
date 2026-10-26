---
title: TryEnter()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba memperoleh kunci eksklusif pada objek yang ditentukan Tidak diimplementasikan.
type: docs
weight: 27
url: /id/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metode

Mencoba memperoleh kunci eksklusif pada objek yang ditentukan Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metode

Mencoba memperoleh kunci eksklusif pada objek yang ditentukan, dan secara atomik menyetel nilai yang menunjukkan apakah kunci diambil.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metode

Mencoba, selama sejumlah milidetik yang ditentukan, memperoleh kunci eksklusif pada objek yang ditentukan Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metode

Mencoba, selama rentang waktu yang ditentukan, memperoleh kunci eksklusif pada objek yang ditentukan Tidak diimplementasikan.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metode

Mencoba, selama rentang waktu yang ditentukan, memperoleh kunci eksklusif pada objek yang ditentukan, dan secara atomik menyetel nilai yang menunjukkan apakah kunci diambil.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metode

Mencoba, selama rentang waktu yang ditentukan, memperoleh kunci eksklusif pada objek yang ditentukan, dan secara atomik menyetel nilai yang menunjukkan apakah kunci diambil.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Monitor](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Ruang Nama [System::Threading](../../)
* Pustaka [Aspose.Slides](../../../)