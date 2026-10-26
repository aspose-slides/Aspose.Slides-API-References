---
title: Receive()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan datagram yang dikirim oleh server.
type: docs
weight: 92
url: /id/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metode


Mengembalikan datagram yang dikirim oleh server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Sebuah [IPEndPoint](../../../system.net/ipendpoint/) yang mewakili host remote dari mana data dikirim. |

### Nilai Kembalian

Array byte di mana data yang diterima akan ditempatkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Kelas [UdpClient](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)