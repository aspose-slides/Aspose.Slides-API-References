---
title: BeginRead()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de leitura assíncrona.
type: docs
weight: 248
url: /pt/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de leitura assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os bytes lidos serão gravados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a ler. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar exclusivamente cada operação de leitura assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de leitura assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)