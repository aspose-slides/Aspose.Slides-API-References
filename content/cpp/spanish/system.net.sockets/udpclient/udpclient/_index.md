---
title: UdpClient()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase UdpClient.
type: docs
weight: 27
url: /es/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() constructor

Inicializa una nueva instancia de la clase [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) constructor

Inicializa una nueva instancia de la clase [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | valor que especifica el esquema de direccionamiento del socket. |

## UdpClient::UdpClient(int32_t) constructor

Inicializa una nueva instancia de la clase [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| port | **int32_t** | el número de puerto local desde el cual deseas comunicarte. |

## UdpClient::UdpClient(int32_t, AddressFamily) constructor

Inicializa una nueva instancia de la clase [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| port | **int32_t** | el número de puerto local desde el cual deseas comunicarte. |
| family | [AddressFamily](../../addressfamily/) | valor que especifica el esquema de direccionamiento del socket. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) constructor

Inicializa una nueva instancia de la clase [UdpClient](../). parámetro local EP el punto de conexión local al que enlazas la conexión UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) constructor

Crea una nueva instancia de la clase [UdpClient](../) y se conecta al host remoto especificado en el puerto especificado.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | el nombre del host DNS remoto al que deseas conectarte. |
| port | **int32_t** | el número de puerto local desde el cual deseas comunicarte. |

## Ver también

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)