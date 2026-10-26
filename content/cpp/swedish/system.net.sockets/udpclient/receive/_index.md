---
title: Receive()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett datagram som skickats av en server.
type: docs
weight: 92
url: /sv/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metod


Returnerar ett datagram som skickats av en server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | En [IPEndPoint](../../../system.net/ipendpoint/) som representerar den fjärrvärd som datan skickades från. |

### Returvärde

En bytearray där mottagen data kommer att tilldelas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Klass [UdpClient](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)