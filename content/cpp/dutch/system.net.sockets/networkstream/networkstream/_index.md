---
title: NetworkStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar.
type: docs
weight: 170
url: /nl/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | De socket die wordt gebruikt voor het verzenden en ontvangen van gegevens. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | De socket die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Geeft het toegangstype aan dat aan de instantie wordt gegeven over de opgegeven socket. |
| ownsSocket | **bool** | Een waarde die aangeeft of de huidige instantie eigendom neemt van de opgegeven socket wanneer de waarde true is. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor

Maakt een nieuw exemplaar.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | De socket die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| ownsSocket | **bool** | Een waarde die aangeeft of de huidige instantie eigendom neemt van de opgegeven socket wanneer de waarde true is. |

## Zie ook

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Socket](../../socket/)
* Klasse [NetworkStream](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)