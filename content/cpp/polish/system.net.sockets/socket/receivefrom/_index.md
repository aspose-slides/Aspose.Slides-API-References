---
title: ReceiveFrom()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.
type: docs
weight: 690
url: /pl/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| size | **int32_t** | Liczba bajtów do odebrania, które zostaną przypisane do określonej tablicy bajtów od indeksu 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie przy odbieraniu. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) metoda

Odbiera dane z określonego punktu końcowego i zapisuje je w określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów, do której zostaną przypisane odebrane dane. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba odebranych bajtów.

## Zobacz także

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)