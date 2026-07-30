---
title: Send()
second_title: Aspose.Slides pro C++ – reference API
description: Odesílá specifikovaná data do socketu.
type: docs
weight: 638
url: /cs/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| size | **int32_t** | Počet bytů ze specifikovaných dat, které se mají odeslat. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| size | **int32_t** | Počet bytů ze specifikovaných dat, které se mají odeslat. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| size | **int32_t** | Počet bytů ze specifikovaných dat, které se mají odeslat. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::ArrayPtr\<uint8_t\>) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) metoda


Odesílá specifikovaná data do socketu.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekce bytových polí, ze kterých mají být data odeslána. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekce bytových polí, ze kterých mají být data odeslána. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekce bytových polí, ze kterých mají být data odeslána. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace odesílání přiřazen kód chyby. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metoda


Odesílá specifikovaná data do socketu.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace odesílání přiřazen kód chyby. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odesílá specifikovaná data do socketu.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace odesílání přiřazen kód chyby. |

### Návratová hodnota

Počet odeslaných bytů.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odesílá specifikovaná data do socketu.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data k odeslání. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| errorCode | [SocketError](../../socketerror/)\& | Výstupní parametr, do kterého bude při selhání operace odesílání přiřazen kód chyby. |

### Návratová hodnota

Počet odeslaných bytů.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)