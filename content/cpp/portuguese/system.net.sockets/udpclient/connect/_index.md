---
title: Connect()
second_title: Referência da API Aspose.Slides para C++
description: Estabelece uma conexão à porta especificada no host especificado.
type: docs
weight: 66
url: /pt/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) método


Estabelece uma conexão à porta especificada no host especificado.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | O nome do host DNS remoto ao qual você pretende conectar. |
| port | **int32_t** | O número da porta local a partir da qual você pretende comunicar. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) método


Estabelece uma conexão com o host no endereço especificado na porta especificada.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | O [IPAddress](../../../system.net/ipaddress/) do host remoto para o qual enviar dados. |
| port | **int32_t** | O número da porta local a partir da qual você pretende comunicar. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) método


Estabelece uma conexão a um ponto de extremidade remoto.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | O ponto de extremidade ao qual você associa a conexão UDP. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)