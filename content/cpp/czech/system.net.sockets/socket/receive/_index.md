---
title: Receive()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přijímá data ze socketu a zapisuje je do určeného pole bajtů.
type: docs
weight: 664
url: /cs/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| size | **int32_t** | Počet bajtů k přijetí. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace přijímání přiřazen kód chyby. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace přijímání přiřazen kód chyby. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Přijímá data ze socketu a zapisuje je do určeného pole bajtů.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Pole bajtů, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet bajtů k přijetí, které budou přiřazeny do určeného pole bajtů od indexu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace přijímání přiřazen kód chyby. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metoda


Přijímá data ze socketu a zapisuje je do určených polí bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Pole bajtů, do nichž budou přiřazena přijatá data. |

### Návratová hodnota

Počet bajtů, které jsou přijaty.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metoda


Přijímá data ze socketu a zapisuje je do určených polí bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Pole bajtů, do nichž budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |

### Návratová hodnota

Počet přijatých bajtů.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metoda


Přijímá data ze socketu a zapisuje je do určených polí bajtů.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Pole bajtů, do nichž budou přiřazena přijatá data. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace přijímání přiřazen kód chyby. |

### Návratová hodnota

Počet přijatých bajtů.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Socket](../)
* Třída [IList](../../../system.collections.generic/ilist/)
* Třída [ArraySegment](../../../system/arraysegment/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)