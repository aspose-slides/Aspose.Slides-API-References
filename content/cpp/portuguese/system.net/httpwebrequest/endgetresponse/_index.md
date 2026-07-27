---
title: EndGetResponse()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a solicitação assíncrona especificada para o recurso seja concluída.
type: docs
weight: 508
url: /pt/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a solicitação assíncrona especificada para o recurso seja concluída.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma solicitação assíncrona para o recurso. |

### Valor de Retorno

A resposta da web.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)