---
title: EndSend()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi pengiriman asinkron yang ditentukan selesai.
type: docs
weight: 508
url: /id/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metode


Menunggu hingga operasi pengiriman asinkron yang ditentukan selesai.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi pengiriman asinkron. |

### Nilai Kembali

Jumlah byte yang dikirim.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metode


Menunggu hingga operasi pengiriman asinkron yang ditentukan selesai.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi pengiriman asinkron. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output di mana kode kesalahan akan diberikan ketika operasi pengiriman gagal. |

### Nilai Kembali

Jumlah byte yang dikirim.

## Lihat Juga

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Socket](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)