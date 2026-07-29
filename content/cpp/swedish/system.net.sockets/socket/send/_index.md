---
title: Send()
second_title: Aspose.Slides för C++ API-referens
description: Skickar den specificerade datan till socketen.
type: docs
weight: 638
url: /sv/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan att skicka. |
| size | **int32_t** | Antalet byte från den specificerade datan som måste skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan att skicka. |
| size | **int32_t** | Antalet byte från den specificerade datan som måste skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan att skicka. |
| size | **int32_t** | Antalet byte från den specificerade datan som måste skickas. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan att skicka. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan att skicka. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan att skicka. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan att skicka. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan att skicka. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method

Skickar den specificerade datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan att skicka. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | En samling av byte-arrayer som datan ska skickas från. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | En samling av byte-arrayer som datan ska skickas från. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | En samling av byte-arrayer som datan ska skickas från. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Skickar den specificerade datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Skickar den specificerade datan till socketen.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### Returvärde

Antalet skickade byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Skickar den specificerade datan till socketen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Datan att skicka. |
| offset | **int32_t** | Offset i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som börjar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden tilldelas när sändningsoperationen misslyckas. |

### Returvärde

Antalet skickade byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Socket](../)
* Klass [IList](../../../system.collections.generic/ilist/)
* Klass [ArraySegment](../../../system/arraysegment/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)