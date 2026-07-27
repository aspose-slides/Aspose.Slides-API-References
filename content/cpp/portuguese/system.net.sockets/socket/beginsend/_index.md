---
title: BeginSend()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de envio assíncrona.
type: docs
weight: 495
url: /pt/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de envio assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um buffer de onde ler os dados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação de envio assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de envio assíncrona iniciada.

## Veja Também

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)