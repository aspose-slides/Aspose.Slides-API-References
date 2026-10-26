---
title: BeginGetResponse()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma solicitação assíncrona para o recurso.
type: docs
weight: 495
url: /pt/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma solicitação assíncrona para o recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um retorno de chamada a ser invocado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar exclusivamente cada operação assíncrona. |

## Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)