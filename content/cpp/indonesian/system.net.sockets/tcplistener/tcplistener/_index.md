---
title: TcpListener()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 53
url: /id/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Titik akhir lokal yang harus diikatkan oleh soket pendengar. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Alamat IP lokal. |
| port | **int32_t** | Nomor port untuk mendengarkan. |

## TcpListener::TcpListener(int32_t) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| port | **int32_t** | Nomor port untuk mendengarkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Kelas [TcpListener](../)
* Kelas [IPAddress](../../../system.net/ipaddress/)
* Ruang Nama [System::Net::Sockets](../../)
* Perpustakaan [Aspose.Slides](../../../)