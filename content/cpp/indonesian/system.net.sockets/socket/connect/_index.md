---
title: Connect()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sambungan ke endpoint remote yang ditentukan.
type: docs
weight: 560
url: /id/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metode


Membuat sambungan ke endpoint remote yang ditentukan.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metode


Membuat sambungan ke endpoint remote yang ditentukan.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Alamat IP host remote. |
| port | **int32_t** | Nomor port host remote. |

## Socket::Connect(String, int32_t) metode


Membuat sambungan ke endpoint remote yang ditentukan.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host remote. |
| port | **int32_t** | Nomor port host remote. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metode


Membuat sambungan ke endpoint remote yang ditentukan.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Alamat IP host remote. |
| port | **int32_t** | Nomor port host remote. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [EndPoint](../../../system.net/endpoint/)
* Kelas [Socket](../)
* Kelas [IPAddress](../../../system.net/ipaddress/)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)