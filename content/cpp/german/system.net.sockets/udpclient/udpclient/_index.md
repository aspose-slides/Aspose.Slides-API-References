---
title: UdpClient()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der UdpClient Klasse.
type: docs
weight: 27
url: /de/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() Konstruktor

Initialisiert eine neue Instanz der [UdpClient](../) Klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) Konstruktor

Initialisiert eine neue Instanz der [UdpClient](../) Klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Wert, der das Adressierungsschema des Sockets angibt. |

## UdpClient::UdpClient(int32_t) Konstruktor

Initialisiert eine neue Instanz der [UdpClient](../) Klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| port | **int32_t** | Die lokale Portnummer, von der aus Sie kommunizieren möchten. |

## UdpClient::UdpClient(int32_t, AddressFamily) Konstruktor

Initialisiert eine neue Instanz der [UdpClient](../) Klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| port | **int32_t** | Die lokale Portnummer, von der aus Sie kommunizieren möchten. |
| family | [AddressFamily](../../addressfamily/) | Wert, der das Adressierungsschema des Sockets angibt. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) Konstruktor

Initialisiert eine neue Instanz der [UdpClient](../) Klasse. param local EP der lokale Endpunkt, an den Sie die UDP-Verbindung binden.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) Konstruktor

Erstellt eine neue Instanz der [UdpClient](../) Klasse und verbindet sich mit dem angegebenen Remote-Host am angegebenen Port.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Der Name des entfernten DNS-Hosts, zu dem Sie eine Verbindung herstellen möchten. |
| port | **int32_t** | Die lokale Portnummer, von der aus Sie kommunizieren möchten. |

## Siehe auch

* Aufzählung [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [UdpClient](../)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)