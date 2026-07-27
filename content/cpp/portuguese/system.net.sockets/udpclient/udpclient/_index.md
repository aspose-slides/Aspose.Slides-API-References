---
title: UdpClient()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe UdpClient.
type: docs
weight: 27
url: /pt/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() construtor


Inicializa uma nova instância da classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) construtor


Inicializa uma nova instância da classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | valor que especifica o esquema de endereçamento do soquete. |

## UdpClient::UdpClient(int32_t) construtor


Inicializa uma nova instância da classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| port | **int32_t** | o número da porta local a partir da qual você pretende comunicar. |

## UdpClient::UdpClient(int32_t, AddressFamily) construtor


Inicializa uma nova instância da classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| port | **int32_t** | o número da porta local a partir da qual você pretende comunicar. |
| family | [AddressFamily](../../addressfamily/) | valor que especifica o esquema de endereçamento do soquete. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) construtor


Inicializa uma nova instância da classe [UdpClient](../). param local EP o ponto de extremidade local ao qual você vincula a conexão UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) construtor


Cria uma nova instância da classe [UdpClient](../) e conecta ao host remoto especificado na porta especificada.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | O nome do host DNS remoto ao qual você pretende conectar. |
| port | **int32_t** | O número da porta local a partir da qual você pretende comunicar. |

## Veja Também

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [UdpClient](../)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)