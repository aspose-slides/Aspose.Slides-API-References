---
title: HttpClient()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 92
url: /fr/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Le gestionnaire HTTP utilisé pour envoyer les requêtes. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | Le gestionnaire HTTP utilisé pour envoyer les requêtes. |
| disposeHandler | **bool** | La valeur indiquant si le gestionnaire doit être libéré lorsque cette instance est libérée. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpClient](../)
* Classe [HttpMessageHandler](../../httpmessagehandler/)
* Espace de noms [System::Net::Http](../../)
* Bibliothèque [Aspose.Slides](../../../)