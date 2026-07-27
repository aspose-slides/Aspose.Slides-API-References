---
title: Send()
second_title: Referência da API Aspose.Slides para C++
description: Envia um datagrama UDP para o host no ponto de extremidade remoto.
type: docs
weight: 79
url: /pt/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Envia um datagrama UDP para o host no ponto de extremidade remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um array do tipo [Byte](../../../system/byte/) para enviar |
| bytes | **int32_t** | O número de bytes no datagrama. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Um [IPEndPoint](../../../system.net/ipendpoint/) que representa o host e a porta para os quais enviar o datagrama. |

### Valor de Retorno

O número de bytes que são enviados.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Envia um datagrama UDP para a porta especificada no host remoto especificado.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um array do tipo [Byte](../../../system/byte/) para enviar |
| bytes | **int32_t** | O número de bytes no datagrama. |
| hostname | [String](../../../system/string/) | Um nome do host remoto. |
| port | **int32_t** | Um número de porta remoto. |

### Valor de Retorno

O número de bytes que são enviados.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Envia um datagrama UDP para um host remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um array do tipo [Byte](../../../system/byte/) para enviar. |
| bytes | **int32_t** | O número de bytes no datagrama. |

### Valor de Retorno

O número de bytes que são enviados.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [UdpClient](../)
* Classe [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)