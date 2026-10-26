---
title: EndGetResponse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource se termine.
type: docs
weight: 287
url: /fr/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) méthode

Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource se termine.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une requête asynchrone pour la ressource. |

### Valeur de retour

La réponse Web.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [WebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)