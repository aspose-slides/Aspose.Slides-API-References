---
title: BeginGetHostAddresses()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry usando la cadena especificada que contiene un nombre de host o una dirección IP.
type: docs
weight: 131
url: /es/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry usando la cadena especificada que contiene un nombre de host o una dirección IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Una cadena que contiene un nombre de host o una dirección IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asíncrona. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [String](../../../system/string/)
* Clase [Object](../../../system/object/)
* Clase [Dns](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)