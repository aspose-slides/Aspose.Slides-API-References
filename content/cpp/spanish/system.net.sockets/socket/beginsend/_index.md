---
title: BeginSend()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de envío asíncrona.
type: docs
weight: 495
url: /es/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) method

Inicia una operación de envío asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un búfer del cual leer datos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada empezando desde el parámetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento del envío. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de manera única cada operación de envío asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de envío asíncrona iniciada.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [Socket](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)