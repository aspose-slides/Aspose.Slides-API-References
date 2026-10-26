---
title: Send()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengirim paket UDP ke host pada titik akhir remote.
type: docs
weight: 79
url: /id/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metode

Sends a UDP datagram to the host at the remote end point.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sebuah array tipe [Byte](../../../system/byte/) untuk dikirim |
| bytes | **int32_t** | Jumlah byte dalam datagram. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Sebuah [IPEndPoint](../../../system.net/ipendpoint/) yang mewakili host dan port untuk mengirim datagram. |

### Nilai Kembali

The number of bytes that are sent.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metode

Sends a UDP datagram to the specified port on the specified remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sebuah array tipe [Byte](../../../system/byte/) untuk dikirim |
| bytes | **int32_t** | Jumlah byte dalam datagram. |
| hostname | [String](../../../system/string/) | Nama host remote. |
| port | **int32_t** | Nomor port remote. |

### Nilai Kembali

The number of bytes that are sent.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metode

Sends a UDP datagram to a remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sebuah array tipe [Byte](../../../system/byte/) untuk dikirim. |
| bytes | **int32_t** | Jumlah byte dalam datagram. |

### Nilai Kembali

The number of bytes that are sent.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Kelas [UdpClient](../)
* Kelas [String](../../../system/string/)
* Ruang nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)