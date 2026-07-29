---
title: Receive()
second_title: Aspose.Slides för C++ API-referens
description: Tar emot data från socketen och skriver den till den angivna bytearrayen.
type: docs
weight: 664
url: /sv/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metod


Tar emot data från socketen och skriver den till den angivna bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där den mottagna datan kommer att tilldelas. |
| offset | **int32_t** | Offset i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och tilldelas den angivna bytearrayen från indexet ”offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metod


Tar emot data från socketen och skriver den till de angivna bytearrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |

### Returvärde

Antalet byte som tas emot.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metod


Tar emot data från socketen och skriver den till de angivna bytearrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |

### Returvärde

Antalet mottagna byte.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metod


Tar emot data från socketen och skriver den till de angivna bytearrayerna.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Bytearrayerna där den mottagna datan kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### Returvärde

Antalet mottagna byte.

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