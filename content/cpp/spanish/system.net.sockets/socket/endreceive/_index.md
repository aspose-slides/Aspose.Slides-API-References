---
title: EndReceive()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera hasta que la operación de recepción asíncrona especificada se complete.
type: docs
weight: 534
url: /es/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) método

Espera hasta que la operación de recepción asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de recepción asíncrona. |

### Valor de retorno

El número de bytes recibidos.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) método

Espera hasta que la operación de recepción asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de recepción asíncrona. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de recepción falle. |

### Valor de retorno

El número de bytes recibidos.

## Ver también

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)