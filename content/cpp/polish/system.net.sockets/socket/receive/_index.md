---
title: Receive()
second_title: Aspose.Slides dla C++ – Referencja API
description: Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 664
url: /pl/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, do którego zostanie przypisany kod błędu, gdy operacja odbioru się nie powiedzie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, do którego zostanie przypisany kod błędu, gdy operacja odbioru się nie powiedzie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metoda


Odbiera dane z gniazda i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu „offset”. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, do którego zostanie przypisany kod błędu, gdy operacja odbioru się nie powiedzie. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metoda


Odbiera dane z gniazda i zapisuje je do określonych tablic bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Tablice bajtów, do których zostaną przypisane odebrane dane. |

### Wartość zwracana

Liczba bajtów, które zostały odebrane.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metoda


Odbiera dane z gniazda i zapisuje je do określonych tablic bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Tablice bajtów, do których zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metoda


Odbiera dane z gniazda i zapisuje je do określonych tablic bajtów.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Tablice bajtów, do których zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbiorze. |
| errorCode | [SocketError](../../socketerror/)\& | Parametr wyjściowy, do którego zostanie przypisany kod błędu, gdy operacja odbioru się nie powiedzie. |

### Wartość zwracana

Liczba odebranych bajtów.

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