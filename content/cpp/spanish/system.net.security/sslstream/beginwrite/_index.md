---
title: BeginWrite()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación de escritura asincrónica.
type: docs
weight: 443
url: /es/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia una operación de escritura asincrónica.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes a la que se escribirán los datos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| count | **int32_t** | El número de bytes a escribir. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de escritura asincrónica. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de escritura asincrónica iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Clase [IAsyncResult](../../../system/iasyncresult/)
* Clase [Object](../../../system/object/)
* Clase [SslStream](../)
* Espacio de nombres [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)