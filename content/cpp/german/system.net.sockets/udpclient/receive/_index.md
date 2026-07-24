---
title: Receive()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein vom Server gesendetes Datagramm zurück.
type: docs
weight: 92
url: /de/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) Methode

Gibt ein vom Server gesendetes Datagramm zurück.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Ein [IPEndPoint](../../../system.net/ipendpoint/) der den Remote-Host repräsentiert, von dem die Daten gesendet wurden. |

### Rückgabewert

Ein Byte-Array, in dem die empfangenen Daten zugewiesen werden.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [UdpClient](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)