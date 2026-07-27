---
title: Receive()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un datagrama enviado por un servidor.
type: docs
weight: 92
url: /es/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) método


Devuelve un datagrama enviado por un servidor.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Un [IPEndPoint](../../../system.net/ipendpoint/) que representa el host remoto desde el cual se enviaron los datos. |

### Valor devuelto

Una matriz de bytes donde se asignarán los datos recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPEndPoint](../../../system.net/ipendpoint/)
* Clase [UdpClient](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)