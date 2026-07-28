---
title: ReceiveFrom()
second_title: Aspose.Slides C++ API referencia
description: Adatokat fogad a megadott végponttól, és a megadott bájt tömbbe írja.
type: docs
weight: 690
url: /hu/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| offset | **int32_t** | A bájt offset az adott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| offset | **int32_t** | A bájt offset az adott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, ahová a fogadott adat kerül. |
| offset | **int32_t** | A bájt offset az adott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, ahová a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma, amely az 'offset' indextől az adott tömbbe lesz helyezve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, ahová a fogadott adat kerül. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Fogad adatokat a megadott végponttól, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, ahová a fogadott adat kerül. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | A távoli végpont. |

### Visszatérési érték

A fogadott bájtok száma.

## Lásd még

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)