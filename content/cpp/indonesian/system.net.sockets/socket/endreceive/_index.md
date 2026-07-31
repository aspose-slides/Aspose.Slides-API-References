---
title: EndReceive()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi penerimaan asinkron yang ditentukan selesai.
type: docs
weight: 534
url: /id/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) metode


Menunggu hingga operasi penerimaan asinkron yang ditentukan selesai.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) metode


Menunggu hingga operasi penerimaan asinkron yang ditentukan selesai.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output dimana kode error akan diberikan ketika operasi penerimaan gagal. |

### Nilai Kembali

Jumlah byte yang diterima.

## Lihat Juga

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)