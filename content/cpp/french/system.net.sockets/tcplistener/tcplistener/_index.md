---
title: TcpListener()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 53
url: /fr/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Le point de terminaison local auquel la socket d'écoute doit être liée. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'adresse IP locale. |
| port | **int32_t** | Un numéro de port à écouter. |

## TcpListener::TcpListener(int32_t) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| port | **int32_t** | Un numéro de port à écouter. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpListener](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)