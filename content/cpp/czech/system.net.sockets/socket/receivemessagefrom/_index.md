---
title: ReceiveMessageFrom()
second_title: Aspose.Slides pro C++ API Reference
description: Přijímá data ze zadaného koncového bodu a zapisuje je do zadaného bytového pole.
type: docs
weight: 677
url: /cs/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metoda


Přijímá data ze zadaného koncového bodu a zapisuje je do zadaného bytového pole.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytové pole, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v zadaném poli. |
| size | **int32_t** | Počet bajtů, které se mají přijmout a budou přiřazeny do zadaného bytového pole od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Výstupní parametr, do kterého budou přiřazeny informace o paketu. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metoda


Přijímá data ze zadaného koncového bodu a zapisuje je do zadaného bytového pole.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytové pole, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v zadaném poli. |
| size | **int32_t** | Počet bajtů, které se mají přijmout a budou přiřazeny do zadaného bytového pole od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Výstupní parametr, do kterého budou přiřazeny informace o paketu. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metoda


Přijímá data ze zadaného koncového bodu a zapisuje je do zadaného bytového pole.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytové pole, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v zadaném poli. |
| size | **int32_t** | Počet bajtů, které se mají přijmout a budou přiřazeny do zadaného bytového pole od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Výstupní parametr, do kterého budou přiřazeny informace o paketu. |

### Návratová hodnota

Počet přijatých bajtů.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [EndPoint](../../../system.net/endpoint/)
* Třída [IPPacketInformation](../../ippacketinformation/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)