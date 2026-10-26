---
title: BeginRead()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi baca asynchronous.
type: docs
weight: 248
url: /id/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi baca asynchronous.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat byte yang dibaca akan dituliskan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan dibaca. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk secara unik mengidentifikasi setiap operasi baca asynchronous. |

### Nilai Pengembalian

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi baca asynchronous yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)