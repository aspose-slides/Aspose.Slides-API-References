---
title: Send()
second_title: Aspose.Slides voor C++ API-referentie
description: Verstuurt de opgegeven gegevens naar de socket.
type: docs
weight: 638
url: /nl/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes van de opgegeven gegevens dat verzonden moet worden. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes van de opgegeven gegevens dat verzonden moet worden. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes van de opgegeven gegevens dat verzonden moet worden. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Een collectie van byte-arrays waaruit gegevens verzonden moeten worden. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Een collectie van byte-arrays waaruit gegevens verzonden moeten worden. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Een collectie van byte-arrays waaruit gegevens verzonden moeten worden. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de verzendoperatie mislukt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de verzendoperatie mislukt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de verzendoperatie mislukt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Verstuurt de opgegeven gegevens naar de socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**>, N\>\& | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de verzendoperatie mislukt. |

### Retourwaarde

Het aantal verzonden bytes.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Socket](../)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [ArraySegment](../../../system/arraysegment/)
* Naamruimte [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)