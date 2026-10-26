---
title: EndGetRequestStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la operación asincrónica especificada para obtener un flujo se complete.
type: docs
weight: 313
url: /es/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación asincrónica especificada para obtener un flujo se complete.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asincrónica para obtener un flujo. |

### Valor devuelto

El flujo para escribir datos en el recurso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [WebRequest](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)