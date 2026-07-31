---
title: BeginSend()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi pengiriman asinkron.
type: docs
weight: 495
url: /id/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi pengiriman asinkron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer untuk membaca data. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi pengiriman asinkron. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi pengiriman asinkron yang dimulai.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [Socket](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)