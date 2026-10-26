---
title: Send()
second_title: Aspose.Slides C++ API referenciája
description: Elküldi a megadott adatot a socketre.
type: docs
weight: 638
url: /hu/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| size | **int32_t** | A megadott adatokból elküldendő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| size | **int32_t** | A megadott adatokból elküldendő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| size | **int32_t** | A megadott adatokból elküldendő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::ArrayPtr\<uint8_t\>) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) metódus


Elküldi a megadott adatot a socketre.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Byte tömbök gyűjteménye, amelyekből adatot kell küldeni. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Byte tömbök gyűjteménye, amelyekből adatot kell küldeni. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Byte tömbök gyűjteménye, amelyekből adatot kell küldeni. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, ahová a hibakód kerül, ha az elküldési művelet meghiúsul. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metódus


Elküldi a megadott adatot a socketre.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, ahová a hibakód kerül, ha az elküldési művelet meghiúsul. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metódus


Elküldi a megadott adatot a socketre.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, ahová a hibakód kerül, ha az elküldési művelet meghiúsul. |

### Visszatérési érték

Az elküldött bájtok száma.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metódus


Elküldi a megadott adatot a socketre.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Az elküldendő adat. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A megadott tömbben az 'offset' paramétertől kezdődő bájtok száma. |
| socketFlags | [SocketFlags](../../socketflags/) | Az elküldés viselkedése. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, ahová a hibakód kerül, ha az elküldési művelet meghiúsul. |

### Visszatérési érték

Az elküldött bájtok száma.

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