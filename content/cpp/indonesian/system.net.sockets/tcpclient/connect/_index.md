---
title: Connect()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat koneksi ke host remote yang ditentukan.
type: docs
weight: 248
url: /id/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metode

Membuat koneksi ke host remote yang ditentukan.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Nama host remote untuk dihubungkan. |
| port | **int32_t** | Port host remote untuk dihubungkan. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metode

Membuat koneksi ke host remote yang ditentukan.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Alamat IP host remote. |
| port | **int32_t** | Port host remote untuk dihubungkan. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metode

Membuat koneksi ke host remote yang ditentukan.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Host remote untuk dihubungkan. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metode

Membuat koneksi ke host remote yang ditentukan.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Alamat-alamat IP host remote. |
| port | **int32_t** | Port host remote untuk dihubungkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [TcpClient](../)
* Kelas [IPAddress](../../../system.net/ipaddress/)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)