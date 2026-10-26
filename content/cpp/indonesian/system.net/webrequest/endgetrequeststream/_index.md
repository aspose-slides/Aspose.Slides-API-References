---
title: EndGetRequestStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi asinkron yang ditentukan untuk memperoleh aliran selesai.
type: docs
weight: 313
url: /id/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metode

Menunggu hingga operasi asinkron yang ditentukan untuk memperoleh aliran selesai.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron untuk mendapatkan aliran. |

### Nilai Kembali

Aliran untuk menulis data ke sumber daya.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [WebRequest](../)
* Ruang Nama [System::Net](../../)
* Library [Aspose.Slides](../../../)