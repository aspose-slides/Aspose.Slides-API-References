---
title: ReceiveFrom()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 690
url: /id/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) metode


Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |

### Nilai Kembali

Jumlah byte yang diterima.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)