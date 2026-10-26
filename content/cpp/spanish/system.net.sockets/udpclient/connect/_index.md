---
title: Connect()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece una conexión al puerto especificado en el host especificado.
type: docs
weight: 66
url: /es/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) método


Establece una conexión al puerto especificado en el host especificado.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | El nombre del host DNS remoto al que desea conectarse. |
| port | **int32_t** | El número de puerto local desde el cual desea comunicarse. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) método


Establece una conexión con el host en la dirección especificada y en el puerto especificado.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | El [IPAddress](../../../system.net/ipaddress/) del host remoto al que enviar datos. |
| port | **int32_t** | El número de puerto local desde el cual desea comunicarse. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) método


Establece una conexión a un punto final remoto.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | el punto final al que enlaza la conexión UDP. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [UdpClient](../)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Clase [IPEndPoint](../../../system.net/ipendpoint/)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)