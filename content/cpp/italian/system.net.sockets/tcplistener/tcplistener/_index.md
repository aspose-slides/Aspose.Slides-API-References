---
title: TcpListener()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 53
url: /it/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | L'endpoint locale a cui il socket listener deve essere associato. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) costruttore


Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'indirizzo IP locale. |
| port | **int32_t** | Un numero di porta su cui ascoltare. |

## TcpListener::TcpListener(int32_t) costruttore


Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| port | **int32_t** | Un numero di porta su cui ascoltare. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpListener](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Spazio dei nomi [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)