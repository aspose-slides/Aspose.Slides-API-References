---
title: ReceiveMessageFrom()
second_title: Aspose.Slides voor C++ API-referentie
description: Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array.
type: docs
weight: 677
url: /nl/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden geplaatst. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | De uitvoerparameter waarin informatie over het pakket wordt geplaatst. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden geplaatst. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | De uitvoerparameter waarin informatie over het pakket wordt geplaatst. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Ontvangt gegevens van het opgegeven eindpunt en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden geplaatst. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | De uitvoerparameter waarin informatie over het pakket wordt geplaatst. |

### Retourwaarde

Het aantal ontvangen bytes.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [EndPoint](../../../system.net/endpoint/)
* Klasse [IPPacketInformation](../../ippacketinformation/)
* Klasse [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)