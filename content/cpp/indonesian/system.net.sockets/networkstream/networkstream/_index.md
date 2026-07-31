---
title: NetworkStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 170
url: /id/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor

Membuat instance baru.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor

Membuat instance baru.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Specifies the access type given to the instance over the specified socket. |
| ownsSocket | **bool** | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor

Membuat instance baru.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |
| ownsSocket | **bool** | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## Lihat Juga

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Socket](../../socket/)
* Kelas [NetworkStream](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)