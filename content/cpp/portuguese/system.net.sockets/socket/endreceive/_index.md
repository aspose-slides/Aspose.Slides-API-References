---
title: EndReceive()
second_title: Aspose.Slides para C++ Referência da API
description: Aguarda até que a operação de recebimento assíncrona especificada seja concluída.
type: docs
weight: 534
url: /pt/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a operação de recebimento assíncrona especificada seja concluída.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação de recebimento assíncrona. |

### Valor de Retorno

O número de bytes que são recebidos.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) método

Aguarda até que a operação de recebimento assíncrona especificada seja concluída.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação de recebimento assíncrona. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de recebimento falhar. |

### Valor de Retorno

O número de bytes recebidos.

## Veja Também

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)