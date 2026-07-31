---
title: BeginWrite()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi penulisan secara asinkron.
type: docs
weight: 274
url: /id/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi penulisan asinkron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer yang berisi data yang akan ditulis. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan ditulis. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang diberikan pengguna untuk mengidentifikasi secara unik setiap operasi penulisan asinkron. |

### Nilai Kembalian

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi penulisan asinkron yang telah dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [NetworkStream](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)