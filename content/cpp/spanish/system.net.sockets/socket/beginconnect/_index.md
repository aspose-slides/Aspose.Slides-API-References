---
title: BeginConnect()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de conexión asíncrona.
type: docs
weight: 573
url: /es/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto final remoto. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación finalice. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación finalice. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | La dirección IP del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación finalice. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Las direcciones IP del host remoto. |
| port | **int32_t** | El número de puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación finalice. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [EndPoint](../../../system.net/endpoint/)
* Clase [Object](../../../system/object/)
* Clase [Socket](../)
* Clase [String](../../../system/string/)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)