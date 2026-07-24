---
title: HttpMessageInvoker()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine neue Instanz.
type: docs
weight: 1
url: /de/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) Konstruktor


Konstruiert eine neue Instanz.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Der HTTP-Handler, der zum Senden von Anfragen verwendet wird. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) Konstruktor


Konstruiert eine neue Instanz.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Der HTTP-Handler, der zum Senden von Anfragen verwendet wird. |
| disposeHandler | **bool** | Der Wert, der angibt, ob der Handler beim Entsorgen dieser Instanz entsorgt werden muss. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpMessageHandler](../../httpmessagehandler/)
* Klasse [HttpMessageInvoker](../)
* Namespace [System::Net::Http](../../)
* Bibliothek [Aspose.Slides](../../../)