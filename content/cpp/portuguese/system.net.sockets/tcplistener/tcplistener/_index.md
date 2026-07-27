---
title: TcpListener()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 53
url: /pt/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | O ponto de extremidade local ao qual o socket do ouvinte deve ser vinculado. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | O endereço IP local. |
| port | **int32_t** | Um número de porta para escutar. |

## TcpListener::TcpListener(int32_t) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| port | **int32_t** | Um número de porta para escutar. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpListener](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)