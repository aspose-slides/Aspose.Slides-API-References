---
title: BeginRead()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de lectura asíncrona.
type: docs
weight: 157
url: /es/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) método

Inicia una operación de lectura asíncrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer para leer |
| offset | int | Un desplazamiento basado en cero en **buffer** que indica la posición desde la cual comenzar a escribir los datos leídos |
| count | int | El número de bytes a leer |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Datos proporcionados por el usuario usados para identificar de manera única cada operación de lectura asíncrona |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de lectura asíncrona iniciada

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)