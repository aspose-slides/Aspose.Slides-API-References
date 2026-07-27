---
title: Connect()
second_title: Aspose.Slides for C++ Referência da API
description: Estabelece uma conexão com o ponto de extremidade remoto especificado.
type: docs
weight: 560
url: /pt/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) método


Estabelece uma conexão com o ponto de extremidade remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | O ponto de extremidade remoto. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) método


Estabelece uma conexão com o ponto de extremidade remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | O endereço IP do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |

## Socket::Connect(String, int32_t) método


Estabelece uma conexão com o ponto de extremidade remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) método


Estabelece uma conexão com o ponto de extremidade remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Os endereços IP do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)