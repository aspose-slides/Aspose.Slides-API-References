---
title: ReceiveMessageFrom()
second_title: Aspose.Slides für C++ API-Referenz
description: Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 677
url: /de/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) Methode


Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes, die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Der Ausgabewert, dem Informationen zum Paket zugewiesen werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) Methode


Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes, die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Der Ausgabewert, dem Informationen zum Paket zugewiesen werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) Methode


Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes, die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Der Ausgabewert, dem Informationen zum Paket zugewiesen werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Siehe auch

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)