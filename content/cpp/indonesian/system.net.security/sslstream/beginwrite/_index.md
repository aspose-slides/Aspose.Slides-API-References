---
title: BeginWrite()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi penulisan secara asinkron.
type: docs
weight: 443
url: /id/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metode


Memulai operasi penulisan asinkron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte untuk menulis data ke. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| count | **int32_t** | Jumlah byte yang akan ditulis. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang dipanggil ketika operasi selesai. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang diberikan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi penulisan asinkron. |

### Nilai Kembali

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous write operation.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [SslStream](../)
* Ruang nama [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)