---
title: QueueUserWorkItem()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan item kerja ke antrean.
type: docs
weight: 1
url: /id/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metode

Menambahkan item kerja ke antrean.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fungsi callback untuk dijalankan. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumen fungsi callback. |

### Nilai Kembali

Selalu mengembalikan true.

## Lihat Juga

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)