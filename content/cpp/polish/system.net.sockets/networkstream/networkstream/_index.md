---
title: NetworkStream()
second_title: Aspose.Slides dla C++ - referencja API
description: Tworzy nową instancję.
type: docs
weight: 170
url: /pl/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Gniazdo, które jest używane do wysyłania i odbierania danych. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Gniazdo, które jest używane do wysyłania i odbierania danych. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Określa typ dostępu przyznany instancji dla określonego gniazda. |
| ownsSocket | **bool** | Wartość, która wskazuje, czy bieżąca instancja przejmuje własność określonego gniazda, gdy wartość jest true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Gniazdo, które jest używane do wysyłania i odbierania danych. |
| ownsSocket | **bool** | Wartość, która wskazuje, czy bieżąca instancja przejmuje własność określonego gniazda, gdy wartość jest true. |

## Zobacz także

* Wyliczenie [FileAccess](../../../system.io/fileaccess/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Socket](../../socket/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)