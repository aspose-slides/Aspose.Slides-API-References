---
title: EndRead()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la operación de lectura asíncrona especificada se complete.
type: docs
weight: 261
url: /es/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación de lectura asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asíncrona |

### Valor devuelto

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [NetworkStream](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)