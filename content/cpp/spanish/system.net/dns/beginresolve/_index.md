---
title: BeginResolve()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación asincrónica para crear una nueva instancia de la clase IPHostEntry utilizando el nombre de host especificado.
type: docs
weight: 157
url: /es/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación asincrónica para crear una nueva instancia de la clase IPHostEntry utilizando el nombre de host especificado.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Un nombre de host que se utiliza para crear una nueva instancia de la clase [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se utilizan para identificar de forma única cada operación asincrónica. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asincrónica iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [String](../../../system/string/)
* Clase [Object](../../../system/object/)
* Clase [Dns](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)