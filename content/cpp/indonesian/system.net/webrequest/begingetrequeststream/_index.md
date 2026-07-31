---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ Referensi API
description: Memulai operasi asinkron untuk mendapatkan aliran guna menulis data ke sumber daya.
type: docs
weight: 300
url: /id/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi asinkron untuk mendapatkan aliran guna menulis data ke sumber daya.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna untuk secara unik mengidentifikasi setiap operasi asinkron. |

### Nilai Kembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [WebRequest](../)
* Ruang Nama [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)