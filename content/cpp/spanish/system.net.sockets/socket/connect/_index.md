---
title: Connect()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece una conexión con el punto final remoto especificado.
type: docs
weight: 560
url: /es/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) método

Establece una conexión con el punto final remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto final remoto. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) método

Establece una conexión con el punto final remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | La dirección IP del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |

## Socket::Connect(String, int32_t) método

Establece una conexión con el punto final remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) método

Establece una conexión con el punto final remoto especificado.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Las direcciones IP del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [EndPoint](../../../system.net/endpoint/)
* Clase [Socket](../)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)