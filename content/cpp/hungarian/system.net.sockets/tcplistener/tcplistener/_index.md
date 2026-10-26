---
title: TcpListener()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre.
type: docs
weight: 53
url: /hu/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor


Új példányt hoz létre.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | A helyi végpont, amelyhez a hallgató socketet kötni kell. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor


Új példányt hoz létre.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A helyi IP-cím. |
| port | **int32_t** | A hallgatáshoz használandó portszám. |

## TcpListener::TcpListener(int32_t) constructor


Új példányt hoz létre.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| port | **int32_t** | A hallgatáshoz használandó portszám. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPEndPoint](../../../system.net/ipendpoint/)
* Osztály [TcpListener](../)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Névterület [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)