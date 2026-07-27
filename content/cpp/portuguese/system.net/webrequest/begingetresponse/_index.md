---
title: BeginGetResponse()
second_title: Referência da API Aspose.Slides for C++
description: Inicia uma solicitação assíncrona para o recurso.
type: docs
weight: 274
url: /pt/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma solicitação assíncrona para o recurso.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Uma função de retorno a ser chamada quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar exclusivamente cada operação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) representando a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [WebRequest](../)
* Espaço de nomes [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)