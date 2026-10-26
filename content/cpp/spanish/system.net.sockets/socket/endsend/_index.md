---
title: EndSend()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera hasta que la operación de envío asíncrona especificada se complete.
type: docs
weight: 508
url: /es/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) método


Espera hasta que la operación de envío asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de envío asíncrona. |

### Valor de retorno

El número de bytes enviados.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) método


Espera hasta que la operación de envío asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de envío asíncrona. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### Valor de retorno

El número de bytes enviados.

## Ver también

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)