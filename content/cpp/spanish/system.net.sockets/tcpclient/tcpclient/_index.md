---
title: TcpClient()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 235
url: /es/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | El punto de conexión al que está enlazado el socket. |

## TcpClient::TcpClient() constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Una familia de direcciones. |

## TcpClient::TcpClient(String, int32_t) constructor

Construye una nueva instancia.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nombre de host remoto al que conectarse. |
| port | **int32_t** | Un puerto del host remoto al que conectarse. |

## Ver también

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)