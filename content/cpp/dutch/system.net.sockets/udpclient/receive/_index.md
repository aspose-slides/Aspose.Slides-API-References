---
title: Receive()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een datagram dat door een server is verzonden.
type: docs
weight: 92
url: /nl/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) method

Retourneert een datagram dat door een server is verzonden.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Een [IPEndPoint](../../../system.net/ipendpoint/) die de externe host vertegenwoordigt van waar de gegevens werden verzonden. |

### Retourwaarde

Een byte-array waarin de ontvangen gegevens worden geplaatst.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [UdpClient](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)