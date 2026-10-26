---
title: EndGetRequestStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la operación asincrónica especificada para obtener un flujo se complete.
type: docs
weight: 157
url: /es/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación asincrónica especificada para obtener un flujo se complete.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asincrónica para obtener un flujo. |

### Valor de retorno

El flujo para escribir datos en el recurso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../../system.io/stream/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [FileWebRequest](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)