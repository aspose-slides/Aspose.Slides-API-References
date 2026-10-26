---
title: EndRead()
second_title: Referencia de API de Aspose.Slides for C++
description: Espera hasta que la operación de lectura asincrónica especificada se complete.
type: docs
weight: 430
url: /es/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación de lectura asincrónica especificada se complete.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de lectura asincrónica |

### Valor devuelto

El número de bytes leídos durante la operación de lectura representada por **asyncResult**

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [SslStream](../)
* Espacio de nombres [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)