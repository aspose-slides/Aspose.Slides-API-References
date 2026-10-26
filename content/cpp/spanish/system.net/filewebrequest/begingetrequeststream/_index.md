---
title: BeginGetRequestStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso.
type: docs
weight: 144
url: /es/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación asíncrona para obtener un flujo para escribir datos en el recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación finalice. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [FileWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)