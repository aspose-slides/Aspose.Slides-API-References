---
title: TcpClient()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 235
url: /pt/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) construtor

Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | O ponto de extremidade ao qual o socket está vinculado. |

## TcpClient::TcpClient() construtor

Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) construtor

Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Uma família de endereços. |

## TcpClient::TcpClient(String, int32_t) construtor

Constrói uma nova instância.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Um nome de host remoto para conectar. |
| port | **int32_t** | Uma porta do host remoto para conectar. |

## Veja Também

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpClient](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)