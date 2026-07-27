---
title: BeginAcceptTcpClient()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de aceptación asíncrona.
type: docs
weight: 170
url: /es/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de aceptación asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un callback que será llamado cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se utilizan para identificar de forma única cada operación de conexión asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de aceptación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [TcpListener](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)