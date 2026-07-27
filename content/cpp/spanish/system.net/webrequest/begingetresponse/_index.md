---
title: BeginGetResponse()
second_title: Aspose.Slides para C++ Referencia de API
description: Inicia una solicitud asíncrona para el recurso.
type: docs
weight: 274
url: /es/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una solicitud asíncrona para el recurso.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un callback que se llamará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se utilizan para identificar de forma única cada operación asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Definición de tipo [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [WebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)