---
title: BeginRead()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de lectura asíncrona.
type: docs
weight: 417
url: /es/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia una operación de lectura asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes de la que se leen los datos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| count | **int32_t** | El número de bytes a leer. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Una función de devolución de llamada que se invoca cuando la operación se completa. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario que se usan para identificar de forma única cada operación de lectura asíncrona. |

### Valor devuelto

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de lectura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [SslStream](../)
* Espacio de nombres [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)