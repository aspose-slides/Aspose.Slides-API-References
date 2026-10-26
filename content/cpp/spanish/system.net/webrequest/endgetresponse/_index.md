---
title: EndGetResponse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la solicitud asíncrona especificada para el recurso se complete.
type: docs
weight: 287
url: /es/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la solicitud asíncrona especificada para el recurso se complete.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una solicitud asíncrona para el recurso. |

### Valor devuelto

La respuesta web.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [WebResponse](../../webresponse/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [WebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)