---
title: BeginGetRequestStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi asinkron untuk mendapatkan aliran guna menulis data ke sumber daya.
type: docs
weight: 469
url: /id/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi asinkron untuk mendapatkan aliran untuk menulis data ke sumber daya.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Kelas [HttpWebRequest](../)
* Ruang Nama [System::Net](../../)
* Library [Aspose.Slides](../../../)