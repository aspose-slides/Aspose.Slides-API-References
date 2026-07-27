---
title: BeginRead()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de lectura asíncrona.
type: docs
weight: 248
url: /es/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de lectura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se escribirán los bytes leídos. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes a leer. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de lectura asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de lectura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)