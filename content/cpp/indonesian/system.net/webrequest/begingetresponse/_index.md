---
title: BeginGetResponse()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai permintaan asinkron untuk sumber daya.
type: docs
weight: 274
url: /id/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai permintaan asinkron untuk sumber daya.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi asinkron. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [WebRequest](../)
* Ruang nama [System::Net](../../)
* Library [Aspose.Slides](../../../)