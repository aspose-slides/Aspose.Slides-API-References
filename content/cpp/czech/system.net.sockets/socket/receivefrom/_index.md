---
title: ReceiveFrom()
second_title: Aspose.Slides pro C++ API Reference
description: Přijímá data ze zadaného koncového bodu a zapisuje je do určeného pole bajtů.
type: docs
weight: 690
url: /cs/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do specifikovaného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Přijímá data z daného koncového bodu a zapisuje je do zadaného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Vzdálený koncový bod. |

### Návratová hodnota

Počet přijatých bajtů.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)