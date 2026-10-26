---
title: Receive()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaad egy szerver által küldött datagrammot.
type: docs
weight: 92
url: /hu/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metódus

Visszaad egy szerver által küldött datagrammot.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Egy [IPEndPoint](../../../system.net/ipendpoint/), amely a távoli gazdagépet jelöli, ahonnan az adatot elküldték. |

### Visszatérési érték

Egy bájttömb, amelyhez a fogadott adatot hozzárendelik.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)