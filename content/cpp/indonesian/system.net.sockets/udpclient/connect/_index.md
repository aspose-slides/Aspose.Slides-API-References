---
title: Connect()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sambungan ke port yang ditentukan pada host yang ditentukan.
type: docs
weight: 66
url: /id/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metode

Membuat sambungan ke port yang ditentukan pada host yang ditentukan.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Nama host DNS remote yang ingin Anda sambungkan. |
| port | **int32_t** | Nomor port lokal yang ingin Anda gunakan untuk berkomunikasi. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metode

Membuat sambungan dengan host pada alamat yang ditentukan di port yang ditentukan.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) dari host remote yang akan dikirim data. |
| port | **int32_t** | Nomor port lokal yang ingin Anda gunakan untuk berkomunikasi. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metode

Membuat sambungan ke titik akhir remote.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | titik akhir yang akan Anda kaitkan dengan koneksi UDP. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [UdpClient](../)
* Kelas [IPAddress](../../../system.net/ipaddress/)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Ruang nama [System::Net::Sockets](../../)
* Pustaka [Aspose.Slides](../../../)