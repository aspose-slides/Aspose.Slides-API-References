---
title: Connect()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en anslutning till den angivna porten på den angivna värden.
type: docs
weight: 66
url: /sv/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metod

Skapar en anslutning till den angivna porten på den angivna värden.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Namnet på den fjärr DNS-värden som du avser att ansluta till. |
| port | **int32_t** | Det lokala portnumret som du avser att kommunicera från. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metod

Skapar en anslutning med värden på den angivna adressen på den angivna porten.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Den [IPAddress](../../../system.net/ipaddress/) för den fjärrvärd till vilken data ska skickas. |
| port | **int32_t** | Det lokala portnumret som du avser att kommunicera från. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metod

Skapar en anslutning till en fjärrändpunkt.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | ändpunkten som du binder UDP-anslutningen till. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [UdpClient](../)
* Klass [IPAddress](../../../system.net/ipaddress/)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)