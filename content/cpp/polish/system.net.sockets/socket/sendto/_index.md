---
title: SendTo()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Wysyła określone dane do określonego punktu końcowego.
type: docs
weight: 651
url: /pl/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy począwszy od parametru 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów w określonej tablicy. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów w określonej tablicy. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| size | **int32_t** | Liczba bajtów w określonej tablicy. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie wysyłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane do wysłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Dane do wysłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Wysyła określone dane do określonego punktu końcowego.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Dane do wysłania. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

### Wartość zwracana

Liczba wysłanych bajtów.

## Zobacz także

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [EndPoint](../../../system.net/endpoint/)
* Klasa [Socket](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)