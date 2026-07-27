---
title: EndGetResponse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la solicitud asincrónica especificada para el recurso se complete.
type: docs
weight: 183
url: /es/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la solicitud asincrónica especificada para el recurso se complete.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una solicitud asincrónica para el recurso. |

### Valor devuelto

La respuesta web.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [WebResponse](../../webresponse/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [FileWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)