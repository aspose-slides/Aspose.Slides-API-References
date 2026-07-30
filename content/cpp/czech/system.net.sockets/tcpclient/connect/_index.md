---
title: Connect()
second_title: Aspose.Slides pro C++ API Reference
description: Naváže spojení se zadaným vzdáleným hostitelem.
type: docs
weight: 248
url: /cs/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metoda

Naváže spojení se zadaným vzdáleným hostitelem.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Název vzdáleného hostitele, ke kterému se připojovat. |
| port | **int32_t** | Port vzdáleného hostitele, ke kterému se připojovat. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda

Naváže spojení se zadaným vzdáleným hostitelem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP adresa vzdáleného hostitele. |
| port | **int32_t** | Port vzdáleného hostitele, ke kterému se připojovat. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metoda

Naváže spojení se zadaným vzdáleným hostitelem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Vzdálený hostitel, ke kterému se připojovat. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metoda

Naváže spojení se zadaným vzdáleným hostitelem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP adresy vzdáleného hostitele. |
| port | **int32_t** | Port vzdáleného hostitele, ke kterému se připojovat. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [TcpClient](../)
* Třída [IPAddress](../../../system.net/ipaddress/)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)