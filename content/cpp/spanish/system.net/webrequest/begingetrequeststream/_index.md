---
title: BeginGetRequestStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación asincrónica para obtener un flujo para escribir datos en el recurso.
type: docs
weight: 300
url: /es/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación asincrónica para obtener un flujo para escribir datos en el recurso.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se utilizan para identificar de forma única cada operación asincrónica. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asincrónica iniciada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [WebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)