---
title: EndGetRequestStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera hasta que la operación asíncrona especificada para obtener un flujo se complete.
type: docs
weight: 482
url: /es/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación asíncrona especificada para obtener un flujo se complete.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asíncrona para obtener un flujo. |

### Valor devuelto

El flujo para escribir datos en el recurso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [HttpWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)