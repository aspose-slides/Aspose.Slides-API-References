---
title: ReceiveMessageFrom()
second_title: Aspose.Slides for C++ API-referencia
description: Adatokat fogad a megadott végpontról, és a megadott bájttömbbe írja.
type: docs
weight: 677
url: /hu/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metódus


Az adatokat a megadott végponttól fogadja, és a megadott bájttömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájttömb, amelybe a fogadott adatokat lesznek hozzárendelve. |
| offset | **int32_t** | A megadott tömbbeli eltolás bájtokban. |
| size | **int32_t** | A kapni kívánt bájtok száma, amely a megadott bájttömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/)\& | A fogadás viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | A kimeneti paraméter, amelybe a csomagról szóló információ kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metódus


Az adatokat a megadott végponttól fogadja, és a megadott bájttömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájttömb, amelybe a fogadott adatokat lesznek hozzárendelve. |
| offset | **int32_t** | A megadott tömbbeli eltolás bájtokban. |
| size | **int32_t** | A kapni kívánt bájtok száma, amely a megadott bájttömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/)\& | A fogadás viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | A kimeneti paraméter, amelybe a csomagról szóló információ kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metódus


Az adatokat a megadott végponttól fogadja, és a megadott bájttömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájttömb, amelybe a fogadott adatokat lesznek hozzárendelve. |
| offset | **int32_t** | A megadott tömbbeli eltolás bájtokban. |
| size | **int32_t** | A kapni kívánt bájtok száma, amely a megadott bájttömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/)\& | A fogadás viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | A kimeneti paraméter, amelybe a csomagról szóló információ kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Lásd még

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [EndPoint](../../../system.net/endpoint/)
* Osztály [IPPacketInformation](../../ippacketinformation/)
* Osztály [Socket](../)
* Névtér [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)