---
title: EndGetResponse()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a solicitação assíncrona especificada para o recurso seja concluída.
type: docs
weight: 287
url: /pt/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a solicitação assíncrona especificada para o recurso seja concluída.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma solicitação assíncrona para o recurso. |

### Valor de Retorno

A resposta da web.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [WebRequest](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)