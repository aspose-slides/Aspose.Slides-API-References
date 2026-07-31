---
title: EndGetRequestStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi asynchronous yang ditentukan untuk mendapatkan aliran selesai.
type: docs
weight: 157
url: /id/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metode

Menunggu hingga operasi asynchronous yang ditentukan untuk mendapatkan aliran selesai.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asynchronous untuk mendapatkan aliran. |

### Nilai Kembali

Aliran untuk menulis data ke sumber daya.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [FileWebRequest](../)
* Ruang Nama [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)