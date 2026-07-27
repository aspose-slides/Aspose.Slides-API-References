---
title: BeginGetRequestStream()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação assíncrona para obter um fluxo para gravar dados no recurso.
type: docs
weight: 144
url: /pt/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação assíncrona para obter um fluxo para gravar dados no recurso.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)