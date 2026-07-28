---
title: Connect()
second_title: Aspose.Slides C++ API-referencia
description: Kapcsolatot hoz létre a megadott távoli kiszolgálóval.
type: docs
weight: 248
url: /hu/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metódus


Létrehoz egy kapcsolatot a megadott távoli kiszolgálóval.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | A kapcsolódáshoz használandó távoli kiszolgáló neve. |
| port | **int32_t** | A távoli kiszolgáló portja, amelyhez csatlakozni kell. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metódus


Létrehoz egy kapcsolatot a megadott távoli kiszolgálóval.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A távoli kiszolgáló IP-címe. |
| port | **int32_t** | A távoli kiszolgáló portja, amelyhez csatlakozni kell. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metódus


Létrehoz egy kapcsolatot a megadott távoli kiszolgálóval.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | A csatlakozandó távoli kiszolgáló. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metódus


Létrehoz egy kapcsolatot a megadott távoli kiszolgálóval.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | A távoli kiszolgáló IP-címei. |
| port | **int32_t** | A távoli kiszolgáló portja, amelyhez csatlakozni kell. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [TcpClient](../)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Osztály [IPEndPoint](../../../system.net/ipendpoint/)
* Névtere [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)