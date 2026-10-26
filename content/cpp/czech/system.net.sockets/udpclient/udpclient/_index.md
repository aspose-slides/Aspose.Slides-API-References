---
title: UdpClient()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Inicializuje novou instanci třídy UdpClient.
type: docs
weight: 27
url: /cs/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() konstruktor

Inicializuje novou instanci třídy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) konstruktor

Inicializuje novou instanci třídy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | hodnota, která určuje schéma adresování socketu. |

## UdpClient::UdpClient(int32_t) konstruktor

Inicializuje novou instanci třídy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| port | **int32_t** | lokální číslo portu, ze kterého chcete komunikovat. |

## UdpClient::UdpClient(int32_t, AddressFamily) konstruktor

Inicializuje novou instanci třídy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| port | **int32_t** | lokální číslo portu, ze kterého chcete komunikovat. |
| family | [AddressFamily](../../addressfamily/) | hodnota, která určuje schéma adresování socketu. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Inicializuje novou instanci třídy [UdpClient](../). param local EP lokální koncový bod, ke kterému připojujete UDP připojení.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) konstruktor

Vytvoří novou instanci třídy [UdpClient](../) a připojí se k určenému vzdálenému hostiteli na určeném portu.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Název vzdáleného DNS hostitele, ke kterému se chcete připojit. |
| port | **int32_t** | Lokální číslo portu, ze kterého chcete komunikovat. |

## Viz také

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [UdpClient](../)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)