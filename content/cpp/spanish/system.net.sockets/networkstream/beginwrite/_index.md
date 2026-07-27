---
title: BeginWrite()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de escritura asíncrona.
type: docs
weight: 274
url: /es/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación de escritura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un búfer que contiene los datos a escribir. |
| offset | **int32_t** | El offset en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes a escribir. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback que se llamará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario usados para identificar de forma única cada operación de escritura asíncrona. |

### Valor devuelto

Un [IAsyncResult](../../../system/iasyncresult/) objeto que representa la operación de escritura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [NetworkStream](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)