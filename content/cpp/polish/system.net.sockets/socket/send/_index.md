---
title: Send()
second_title: Referencja API Aspose.Slides for C++
description: Wysyła określone dane do gniazda.
type: docs
weight: 638
url: /pl/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów z podanych danych, które należy wysłać. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów z podanych danych, które należy wysłać. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów z podanych danych, które należy wysłać. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method

Wysyła określone dane do gniazda.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekcja tablic bajtów, z których należy wysłać dane. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekcja tablic bajtów, z których należy wysłać dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Kolekcja tablic bajtów, z których należy wysłać dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja wysyłania się nie powiedzie. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Wysyła określone dane do gniazda.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja wysyłania się nie powiedzie. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Wysyła określone dane do gniazda.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja wysyłania się nie powiedzie. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Wysyła określone dane do gniazda.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, w którym zostanie przypisany kod błędu, gdy operacja wysyłania się nie powiedzie. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Zobacz także

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)