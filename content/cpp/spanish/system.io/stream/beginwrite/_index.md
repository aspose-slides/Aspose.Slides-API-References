---
title: BeginWrite()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de escritura asincrónica.
type: docs
weight: 170
url: /es/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) método

Inicia una operación de escritura asincrónica.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer que contiene los datos a escribir |
| offset | int | Un desplazamiento basado en cero en **buffer** que indica la posición desde la cual comienzan los datos a escribir |
| count | int | El número de bytes a escribir |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de escritura asincrónica |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de escritura asincrónica iniciada

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [Stream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)