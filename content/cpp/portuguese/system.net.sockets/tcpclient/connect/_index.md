---
title: Connect()
second_title: Referência da API Aspose.Slides para C++
description: Estabelece uma conexão com o host remoto especificado.
type: docs
weight: 248
url: /pt/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) method

Estabelece uma conexão com o host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Um nome de host remoto para conectar. |
| port | **int32_t** | Uma porta do host remoto para conectar. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method

Estabelece uma conexão com o host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | O endereço IP de um host remoto. |
| port | **int32_t** | Uma porta do host remoto para conectar. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) method

Estabelece uma conexão com o host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Um host remoto para conectar. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) method

Estabelece uma conexão com o host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Os endereços IP de um host remoto. |
| port | **int32_t** | Uma porta do host remoto para conectar. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)