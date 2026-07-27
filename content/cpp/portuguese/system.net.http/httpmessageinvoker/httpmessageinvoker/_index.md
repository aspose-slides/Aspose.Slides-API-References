---
title: HttpMessageInvoker()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 1
url: /pt/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | O manipulador HTTP usado para enviar solicitações. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | O manipulador HTTP usado para enviar solicitações. |
| disposeHandler | **bool** | O valor que indica se o manipulador deve ser descartado quando esta instância for descartada. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpMessageHandler](../../httpmessagehandler/)
* Class [HttpMessageInvoker](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)