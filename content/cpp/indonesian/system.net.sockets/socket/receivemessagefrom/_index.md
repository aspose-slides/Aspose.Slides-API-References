---
title: ReceiveMessageFrom()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 677
url: /id/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte dimana data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parameter output dimana informasi tentang paket akan ditempatkan. |

### Nilai Kembalian

Jumlah byte yang diterima.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte dimana data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parameter output dimana informasi tentang paket akan ditempatkan. |

### Nilai Kembalian

Jumlah byte yang diterima.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Menerima data dari endpoint yang ditentukan dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte dimana data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan akan ditempatkan ke array byte yang ditentukan mulai dari indeks 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Perilaku penerimaan. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Endpoint remote. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parameter output dimana informasi tentang paket akan ditempatkan. |

### Nilai Kembalian

Jumlah byte yang diterima.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [EndPoint](../../../system.net/endpoint/)
* Kelas [IPPacketInformation](../../ippacketinformation/)
* Kelas [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)