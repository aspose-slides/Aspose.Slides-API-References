---
title: QueueUserWorkItem()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan item kerja ke antrean dengan callback tanpa parameter.
type: docs
weight: 14
url: /id/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metode

Menambahkan item kerja ke antrean dengan callback tanpa parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fungsi callback yang akan digunakan sebagai pekerjaan. |

### Nilai Kembalian

Selalu mengembalikan true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metode

Menambahkan item kerja ke antrean dengan callback tanpa parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fungsi callback yang akan digunakan sebagai pekerjaan. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parameter fungsi pekerjaan. |

### Nilai Kembalian

Selalu mengembalikan true.

## Lihat Juga

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ThreadPool](../)
* Kelas [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)