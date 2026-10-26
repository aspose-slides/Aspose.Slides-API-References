---
title: HttpMessageInvoker()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 1
url: /it/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Il gestore HTTP usato per inviare le richieste. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Il gestore HTTP usato per inviare le richieste. |
| disposeHandler | **bool** | Il valore che indica se il gestore deve essere eliminato quando questa istanza viene eliminata. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpMessageHandler](../../httpmessagehandler/)
* Classe [HttpMessageInvoker](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)