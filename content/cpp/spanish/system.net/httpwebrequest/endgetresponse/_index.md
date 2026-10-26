---
title: EndGetResponse()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera hasta que la solicitud asincrónica especificada para el recurso se complete.
type: docs
weight: 508
url: /es/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la solicitud asincrónica especificada para el recurso se complete.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Clase [HttpWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)