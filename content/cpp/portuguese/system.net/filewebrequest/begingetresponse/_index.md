---
title: BeginGetResponse()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma solicitação assíncrona para o recurso.
type: docs
weight: 170
url: /pt/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma solicitação assíncrona para o recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um retorno de chamada a ser invocado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar unicamente cada operação assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) representando a operação assíncrona iniciada.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)