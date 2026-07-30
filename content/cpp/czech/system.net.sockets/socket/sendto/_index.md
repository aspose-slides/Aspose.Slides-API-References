---
title: SendTo()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odesílá zadaná data na zadaný koncový bod.
type: docs
weight: 651
url: /cs/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method

Odesílá určená data na určený koncový bod.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

### Návratová hodnota

Počet odeslaných bajtů.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)