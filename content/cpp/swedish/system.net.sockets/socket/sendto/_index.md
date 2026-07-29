---
title: SendTo()
second_title: Aspose.Slides för C++ API-referens
description: Skickar den angivna datan till den angivna slutpunkten.
type: docs
weight: 651
url: /sv/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan som ska skickas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte i den angivna arrayen med start från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan som ska skickas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte i den angivna arrayen med start från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan som ska skickas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte i den angivna arrayen med start från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan som ska skickas. |
| size | **int32_t** | Antalet byte i den angivna arrayen. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan som ska skickas. |
| size | **int32_t** | Antalet byte i den angivna arrayen. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan som ska skickas. |
| size | **int32_t** | Antalet byte i den angivna arrayen. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan som ska skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan som ska skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan som ska skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan som ska skickas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan som ska skickas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) metod

Skickar den angivna datan till den angivna slutpunkten.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan som ska skickas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Den fjärrslutpunkten. |

### Returvärde

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [EndPoint](../../../system.net/endpoint/)
* Klass [Socket](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)