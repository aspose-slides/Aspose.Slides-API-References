---
title: ReceiveMessageFrom()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.
type: docs
weight: 677
url: /pl/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, w której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parametr wyjściowy, w którym zostaną przypisane informacje o pakiecie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, w której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parametr wyjściowy, w którym zostaną przypisane informacje o pakiecie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, w której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Parametr wyjściowy, w którym zostaną przypisane informacje o pakiecie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Zobacz także

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [EndPoint](../../../system.net/endpoint/)
* Klasa [IPPacketInformation](../../ippacketinformation/)
* Klasa [Socket](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)