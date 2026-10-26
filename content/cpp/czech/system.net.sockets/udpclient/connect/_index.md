---
title: Connect()
second_title: Reference API pro C++ Aspose.Slides
description: Naváže spojení se zadaným portem na určeném hostiteli.
type: docs
weight: 66
url: /cs/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metoda

Navazuje spojení se zadaným portem na zadaném hostiteli.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Název vzdáleného DNS hostitele, ke kterému se chcete připojit. |
| port | **int32_t** | Číslo místního portu, ze kterého chcete komunikovat. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda

Navazuje spojení s hostitelem na zadané adrese a portu.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) vzdáleného hostitele, na který se mají posílat data. |
| port | **int32_t** | Číslo místního portu, ze kterého chcete komunikovat. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metoda

Navazuje spojení se vzdáleným koncovým bodem.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | koncový bod, ke kterému svážete spojení UDP. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)