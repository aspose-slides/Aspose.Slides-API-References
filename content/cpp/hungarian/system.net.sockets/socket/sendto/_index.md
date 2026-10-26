---
title: SendTo()
second_title: Aspose.Slides C++ API referencia
description: Elküldi a megadott adatot a megadott végpontra.
type: docs
weight: 651
url: /hu/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma, amely a ‘offset’ paramétertől kezdődik. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma, amely a ‘offset’ paramétertől kezdődik. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma, amely a ‘offset’ paramétertől kezdődik. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| size | **int32_t** | A megadott tömbben lévő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Elküldi a megadott adatot a megadott végpontra.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

### Visszatérési érték

A elküldött bájtok száma.

## Lásd még

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)