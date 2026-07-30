---
title: HttpClient()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 92
url: /it/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() costruttore

Crea una nuova istanza.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) costruttore

Crea una nuova istanza.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | L'handler HTTP usato per inviare le richieste. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) costruttore

Crea una nuova istanza.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | L'handler HTTP usato per inviare le richieste. |
| disposeHandler | **bool** | Il valore che indica se l'handler deve essere eliminato quando questa istanza viene eliminata. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpClient](../)
* Classe [HttpMessageHandler](../../httpmessagehandler/)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)