---
title: Receive()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací datagram odeslaný serverem.
type: docs
weight: 92
url: /cs/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metoda

Vrací datagram odeslaný serverem.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Instance [IPEndPoint](../../../system.net/ipendpoint/) představující vzdálený host, ze kterého byla data odeslána. |

### Návratová hodnota

Pole bajtů, do kterého budou přiřazena přijatá data.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Třída [UdpClient](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)