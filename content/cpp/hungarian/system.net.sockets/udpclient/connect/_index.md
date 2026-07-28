---
title: Connect()
second_title: Aspose.Slides for C++ API-referencia
description: Kapcsolatot hoz létre a megadott porton a megadott kiszolgálón.
type: docs
weight: 66
url: /hu/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metódus


Kapcsolatot hoz létre a megadott porton a megadott kiszolgálón.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | A távoli DNS-kiszolgáló neve, amelyhez csatlakozni kíván. |
| port | **int32_t** | A helyi port száma, amelyről kommunikálni kíván. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metódus


Kapcsolatot hoz létre a megadott címen lévő kiszolgálóval a megadott porton.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A távoli kiszolgáló [IPAddress](../../../system.net/ipaddress/)-ja, amelyhez adatot küldeni kíván. |
| port | **int32_t** | A helyi port száma, amelyről kommunikálni kíván. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metódus


Kapcsolatot hoz létre egy távoli végponttal.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | a végpont, amelyhez a UDP kapcsolatot kötöd. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [UdpClient](../)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Osztály [IPEndPoint](../../../system.net/ipendpoint/)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)