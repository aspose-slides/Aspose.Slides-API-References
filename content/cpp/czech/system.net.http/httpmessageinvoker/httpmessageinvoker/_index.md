---
title: HttpMessageInvoker()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci.
type: docs
weight: 1
url: /cs/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler používaný k odesílání požadavků. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | HTTP handler používaný k odesílání požadavků. |
| disposeHandler | **bool** | Hodnota, která určuje, zda má být handler uvolněn, když je tato instance uvolněna. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [HttpMessageHandler](../../httpmessagehandler/)
* Třída [HttpMessageInvoker](../)
* Jmenný prostor [System::Net::Http](../../)
* Knihovna [Aspose.Slides](../../../)