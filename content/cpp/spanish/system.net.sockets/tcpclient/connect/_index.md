---
title: Connect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece una conexión con el host remoto especificado.
type: docs
weight: 248
url: /es/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) método


Establece una conexión con el host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nombre de host remoto al que conectar. |
| port | **int32_t** | Un puerto del host remoto al que conectar. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) método


Establece una conexión con el host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | La dirección IP de un host remoto. |
| port | **int32_t** | Un puerto del host remoto al que conectar. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) método


Establece una conexión con el host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un host remoto al que conectar. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) método


Establece una conexión con el host remoto especificado.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Las direcciones IP de un host remoto. |
| port | **int32_t** | Un puerto del host remoto al que conectar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [TcpClient](../)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Clase [IPEndPoint](../../../system.net/ipendpoint/)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)