---
title: Send()
second_title: Referencia de API de Aspose.Slides for C++
description: Envía un datagrama UDP al host en el punto final remoto.
type: docs
weight: 79
url: /es/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) método


Envía un datagrama UDP al host en el punto final remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar |
| bytes | **int32_t** | El número de bytes en el datagrama. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un [IPEndPoint](../../../system.net/ipendpoint/) que representa el host y el puerto al que se enviará el datagrama. |

### Valor devuelto

El número de bytes que se envían.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) método


Envía un datagrama UDP al puerto especificado en el host remoto especificado.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar |
| bytes | **int32_t** | El número de bytes en el datagrama. |
| hostname | [String](../../../system/string/) | Un nombre del host remoto. |
| port | **int32_t** | Un número de puerto remoto. |

### Valor devuelto

El número de bytes que se envían.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) método


Envía un datagrama UDP a un host remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar. |
| bytes | **int32_t** | El número de bytes en el datagrama. |

### Valor devuelto

El número de bytes que se envían.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPEndPoint](../../../system.net/ipendpoint/)
* Clase [UdpClient](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)