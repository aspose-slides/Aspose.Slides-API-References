---
title: BeginWrite()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de gravação assíncrona.
type: docs
weight: 274
url: /pt/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de gravação assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um buffer contendo os dados a serem gravados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a gravar. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar exclusivamente cada operação de gravação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de gravação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)