---
title: BeginReceive()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicia una operación de escritura asíncrona.
type: docs
weight: 521
url: /es/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de escritura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un búfer donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se ejecutará cuando la operación se complete. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos provistos por el usuario utilizados para identificar de forma única cada operación de recepción asíncrona. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de recepción asíncrona iniciada.

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