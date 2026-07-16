---
title: HttpMessageInvoker()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 1
url: /fr/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Le gestionnaire HTTP utilisé pour envoyer les requêtes. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Le gestionnaire HTTP utilisé pour envoyer les requêtes. |
| disposeHandler | **bool** | La valeur qui indique si le gestionnaire doit être libéré lorsque cette instance est libérée. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpMessageHandler](../../httpmessagehandler/)
* Classe [HttpMessageInvoker](../)
* Espace de noms [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)