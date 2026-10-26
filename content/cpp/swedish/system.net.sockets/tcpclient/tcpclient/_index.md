---
title: TcpClient()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 235
url: /sv/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Slutpunkten som socketen är bunden till. |

## TcpClient::TcpClient() konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | En adressfamilj. |

## TcpClient::TcpClient(String, int32_t) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Ett fjärrvärdsnamn att ansluta till. |
| port | **int32_t** | En port på fjärrvärden att ansluta till. |

## Se även

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)