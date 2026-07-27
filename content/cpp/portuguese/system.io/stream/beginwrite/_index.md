---
title: BeginWrite()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de escrita assíncrona.
type: docs
weight: 170
url: /pt/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) método

Inicia uma operação de escrita assíncrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um buffer contendo dados a serem escritos |
| offset | int | Um deslocamento baseado em zero em **buffer** indicando a posição a partir da qual os dados a serem escritos começam |
| count | int | O número de bytes a escrever |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação de escrita assíncrona |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) representando a operação de escrita assíncrona iniciada

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* classe [IAsyncResult](../../../system/iasyncresult/)
* classe [Object](../../../system/object/)
* classe [Stream](../)
* namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)