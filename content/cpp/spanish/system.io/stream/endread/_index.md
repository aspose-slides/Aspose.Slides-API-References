---
title: EndRead()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la operación de lectura asincrónica especificada se complete.
type: docs
weight: 183
url: /es/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) método


Espera hasta que la operación de lectura asincrónica especificada se complete.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asincrónica |

### Valor devuelto

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Stream](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)