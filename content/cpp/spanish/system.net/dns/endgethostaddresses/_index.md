---
title: EndGetHostAddresses()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera hasta que la operación asincrónica especificada para crear una nueva instancia de la clase IPHostEntry-class finalice.
type: docs
weight: 144
url: /es/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación asincrónica especificada para crear una nueva instancia de la clase IPHostEntry-class finalice.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación asincrónica. |

### Valor de retorno

Una nueva instancia de la clase IPHostEntry-class.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPAddress](../../ipaddress/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Dns](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)