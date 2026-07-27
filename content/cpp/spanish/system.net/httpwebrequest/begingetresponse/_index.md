---
title: BeginGetResponse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicia una solicitud asíncrona para el recurso.
type: docs
weight: 495
url: /es/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una solicitud asíncrona para el recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una función de devolución de llamada que se invoca cuando la operación se completa. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asíncrona. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [HttpWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)