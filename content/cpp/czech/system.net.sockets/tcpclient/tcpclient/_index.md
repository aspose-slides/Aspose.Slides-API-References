---
title: TcpClient()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří novou instanci.
type: docs
weight: 235
url: /cs/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Konecný bod, ke kterému je socket připojen. |

## TcpClient::TcpClient() konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Rodina adres. |

## TcpClient::TcpClient(String, int32_t) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Název vzdáleného hostitele, ke kterému se připojit. |
| port | **int32_t** | Port vzdáleného hostitele, ke kterému se připojit. |

## Viz také

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Třída [TcpClient](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)