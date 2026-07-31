---
title: SendTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengirim data yang ditentukan ke endpoint yang ditentukan.
type: docs
weight: 651
url: /id/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan mulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan mulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan mulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Mengirim data yang ditentukan ke endpoint yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Endpoint remote. |

### Nilai Kembalian

Jumlah byte yang dikirim.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)