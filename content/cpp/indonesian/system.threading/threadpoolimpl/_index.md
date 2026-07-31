---
title: ThreadPoolImpl
second_title: Referensi API Aspose.Slides untuk C++
description: Data internal thread pool. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses. Anda tidak boleh membuat instance secara langsung.
type: docs
weight: 235
url: /id/system.threading/threadpoolimpl/
---
## ThreadPoolImpl kelas

[Thread](../thread/) data internal pool. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses(s). Anda tidak boleh membuat instance secara langsung.

```cpp
class ThreadPoolImpl
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Mendapatkan jumlah thread yang tersedia. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Mendapatkan status inisialisasi singleton. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Mendapatkan jumlah maksimal thread bersamaan. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Mendapatkan jumlah minimal thread yang dibuat oleh pool. |
| void [JoinAll](./joinall/)() | Menggabungkan semua thread yang dimiliki. Menunggu tanpa batas. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Menambahkan item kerja ke antrian. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Mengatur jumlah thread yang dimiliki oleh pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Mengatur jumlah minimal thread yang dimiliki oleh pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Konstruktor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destruktor. Menggabungkan semua thread jika belum dihentikan. |

## Lihat Juga

* Ruang nama [System::Threading](../)
* Perpustakaan [Aspose.Slides](../../)