---
title: BeginReceive()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi penulisan asinkron.
type: docs
weight: 521
url: /id/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi penulisan asinkron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sebuah buffer tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan mulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi penerimaan asinkron. |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi penerimaan asinkron yang dimulai.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Pustaka [Aspose.Slides](../../../)