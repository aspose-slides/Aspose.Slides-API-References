---
title: TcpListener()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 53
url: /es/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | El punto de conexión local al que debe enlazarse el socket del listener. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | La dirección IP local. |
| port | **int32_t** | Un número de puerto para escuchar. |

## TcpListener::TcpListener(int32_t) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| port | **int32_t** | Un número de puerto para escuchar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPEndPoint](../../../system.net/ipendpoint/)
* Clase [TcpListener](../)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)