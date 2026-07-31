---
title: UdpClient()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi sebuah instance baru dari kelas UdpClient.
type: docs
weight: 27
url: /id/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() konstruktor

Menginisialisasi sebuah instance baru dari kelas [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) konstruktor

Menginisialisasi sebuah instance baru dari kelas [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | nilai yang menentukan skema pengalamatan socket. |

## UdpClient::UdpClient(int32_t) konstruktor

Menginisialisasi sebuah instance baru dari kelas [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| port | **int32_t** | nomor port lokal yang akan Anda gunakan untuk berkomunikasi. |

## UdpClient::UdpClient(int32_t, AddressFamily) konstruktor

Menginisialisasi sebuah instance baru dari kelas [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| port | **int32_t** | nomor port lokal yang akan Anda gunakan untuk berkomunikasi. |
| family | [AddressFamily](../../addressfamily/) | nilai yang menentukan skema pengalamatan socket. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Menginisialisasi sebuah instance baru dari kelas [UdpClient](../). param local EP endpoint lokal tempat Anda mengikat koneksi UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) konstruktor

Membuat sebuah instance baru dari kelas [UdpClient](../) dan menyambungkan ke host remote yang ditentukan pada port yang ditentukan.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Nama host DNS remote yang ingin Anda sambungkan. |
| port | **int32_t** | nomor port lokal yang akan Anda gunakan untuk berkomunikasi. |

## Lihat Juga

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [UdpClient](../)
* Kelas [IPEndPoint](../../../system.net/ipendpoint/)
* Kelas [String](../../../system/string/)
* ruang nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)