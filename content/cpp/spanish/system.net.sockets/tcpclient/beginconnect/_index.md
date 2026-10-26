---
title: BeginConnect()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de conexión asíncrona.
type: docs
weight: 261
url: /es/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | Un nombre de host remoto. |
| port | **int32_t** | Un puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario usados para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | La dirección IP de un host remoto. |
| port | **int32_t** | Un puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario usados para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Las direcciones IP de un host remoto. |
| port | **int32_t** | Un puerto del host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario usados para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [String](../../../system/string/)
* Clase [Object](../../../system/object/)
* Clase [TcpClient](../)
* Clase [IPAddress](../../../system.net/ipaddress/)
* Espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)