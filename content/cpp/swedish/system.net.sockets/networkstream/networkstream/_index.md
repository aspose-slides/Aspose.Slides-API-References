---
title: NetworkStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 170
url: /sv/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) konstruktör


Skapar en ny instans.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Den socket som används för att skicka och ta emot data. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) konstruktör


Skapar en ny instans.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Den socket som används för att skicka och ta emot data. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Anger åtkomsttypen som ges till instansen över den angivna socketen. |
| ownsSocket | **bool** | Ett värde som indikerar om den aktuella instansen tar ägandeskap över den angivna socketen när värdet är sant. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) konstruktör


Skapar en ny instans.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Den socket som används för att skicka och ta emot data. |
| ownsSocket | **bool** | Ett värde som indikerar om den aktuella instansen tar ägandeskap över den angivna socketen när värdet är sant. |

## Se även

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Socket](../../socket/)
* Klass [NetworkStream](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)