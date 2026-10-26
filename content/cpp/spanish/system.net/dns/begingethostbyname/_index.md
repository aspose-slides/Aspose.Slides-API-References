---
title: BeginGetHostByName()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry usando el nombre de host especificado.
type: docs
weight: 53
url: /es/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación asíncrona para crear una nueva instancia de la clase IPHostEntry usando el nombre de host especificado.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Un nombre de host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asíncrona. |

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