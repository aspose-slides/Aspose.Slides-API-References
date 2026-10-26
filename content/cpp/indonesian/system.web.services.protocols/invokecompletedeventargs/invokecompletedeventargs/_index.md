---
title: InvokeCompletedEventArgs()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 14
url: /id/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

Membuat sebuah instance baru.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Setiap kesalahan yang terjadi selama operasi asinkron. |
| cancelled | **bool** | Nilai yang menunjukkan apakah operasi asinkron dibatalkan. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objek status opsional yang diberikan oleh pengguna dan diteruskan ke metode [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Sekumpulan hasil operasi asinkron. |

## Lihat Juga

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Object](../../../system/object/)
* Kelas [InvokeCompletedEventArgs](../)
* Ruang Nama [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)