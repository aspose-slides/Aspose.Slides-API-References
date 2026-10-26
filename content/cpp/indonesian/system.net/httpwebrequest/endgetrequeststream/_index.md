---
title: EndGetRequestStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi asinkron yang ditentukan untuk mendapatkan aliran selesai.
type: docs
weight: 482
url: /id/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metode

Menunggu sampai operasi asinkron yang ditentukan untuk mendapatkan aliran selesai.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Kelas [HttpWebRequest](../)
* Ruang Nama [System::Net](../../)
* Pustaka [Aspose.Slides](../../../)