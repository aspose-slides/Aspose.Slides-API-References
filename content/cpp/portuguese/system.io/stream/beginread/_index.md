---
title: BeginRead()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de leitura assíncrona.
type: docs
weight: 157
url: /pt/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) método


Inicia uma operação de leitura assíncrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Um buffer para onde ler |
| offset | int | Um deslocamento baseado em zero em **buffer** indicando a posição a partir da qual começar a gravar os dados lidos |
| count | int | O número de bytes a ler |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação de leitura assíncrona |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de leitura assíncrona iniciada

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)