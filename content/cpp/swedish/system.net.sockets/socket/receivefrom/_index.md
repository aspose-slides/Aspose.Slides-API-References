---
title: ReceiveFrom()
second_title: Aspose.Slides för C++ API-referens
description: Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.
type: docs
weight: 690
url: /sv/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| offset | **int32_t** | Offseten i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| offset | **int32_t** | Offseten i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Byte-arrayen där de mottagna data kommer att tilldelas. |
| offset | **int32_t** | Offseten i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Byte-arrayen där de mottagna data kommer att tilldelas. |
| size | **int32_t** | Antalet byte som ska tas emot och som kommer att tilldelas den angivna byte-arrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayen där de mottagna data kommer att tilldelas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Mottar data från den angivna slutpunkten och skriver den till den angivna byte-arrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Byte-arrayen där de mottagna data kommer att tilldelas. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärranslutna slutpunkten. |

### Returvärde

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [EndPoint](../../../system.net/endpoint/)
* Klass [Socket](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)