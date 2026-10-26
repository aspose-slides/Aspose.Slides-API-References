---
title: Receive()
second_title: Aspose.Slides for C++ API-referencia
description: Adatot fogad a socketből, és a megadott bájt tömbbe írja.
type: docs
weight: 664
url: /hu/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, amelybe a fogadott adat kerül. |
| size | **int32_t** | A fogadandó bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, amelybe a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, amelybe a fogadott adat kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, amelybe a hibakód kerül, ha a fogadási művelet hibát eredményez. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, amelybe a hibakód kerül, ha a fogadási művelet hibát eredményez. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metódus

Adatot fogad a socketből, és a megadott bájt tömbbe írja.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | A bájt tömb, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A fogadandó bájtok száma, amely a megadott bájt tömbbe kerül az 'offset' indextől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, amelybe a hibakód kerül, ha a fogadási művelet hibát eredményez. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metódus

Adatot fogad a socketből, és a megadott bájt tömbökbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A bájt tömbök, amelyekbe a fogadott adat kerül. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metódus

Adatot fogad a socketből, és a megadott bájt tömbökbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A bájt tömbök, amelyekbe a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metódus

Adatot fogad a socketből, és a megadott bájt tömbökbe írja.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A bájt tömbök, amelyekbe a fogadott adat kerül. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, amelybe a hibakód kerül, ha a fogadási művelet hibát eredményez. |

### Visszatérési érték

A fogadott bájtok száma.

## Lásd még

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)