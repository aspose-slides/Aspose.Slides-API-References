---
title: EndSend()
second_title: Referência da API Aspose.Slides para C++
description: Espera até que a operação assíncrona de envio especificada seja concluída.
type: docs
weight: 508
url: /pt/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a operação assíncrona de envio especificada seja concluída.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação assíncrona de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) método

Aguarda até que a operação assíncrona de envio especificada seja concluída.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação assíncrona de envio. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de envio falhar. |

### Valor de Retorno

O número de bytes enviados.

## Veja Também

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)