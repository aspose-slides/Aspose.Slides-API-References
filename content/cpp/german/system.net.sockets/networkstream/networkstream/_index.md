---
title: NetworkStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt eine neue Instanz.
type: docs
weight: 170
url: /de/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor

Erzeugt eine neue Instanz.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Der Socket, der zum Senden und Empfangen von Daten verwendet wird. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor

Erzeugt eine neue Instanz.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Der Socket, der zum Senden und Empfangen von Daten verwendet wird. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Gibt den Zugriffstyp an, der der Instanz über den angegebenen Socket gewährt wird. |
| ownsSocket | **bool** | Ein Wert, der angibt, ob die aktuelle Instanz das Eigentum am angegebenen Socket übernimmt, wenn der Wert true ist. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor

Erzeugt eine neue Instanz.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Der Socket, der zum Senden und Empfangen von Daten verwendet wird. |
| ownsSocket | **bool** | Ein Wert, der angibt, ob die aktuelle Instanz das Eigentum am angegebenen Socket übernimmt, wenn der Wert true ist. |

## Siehe auch

* Aufzählung [FileAccess](../../../system.io/fileaccess/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [Socket](../../socket/)
* Klasse [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)