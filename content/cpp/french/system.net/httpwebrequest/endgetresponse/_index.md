---
title: EndGetResponse()
second_title: Référence API Aspose.Slides pour C++
description: Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource soit terminée.
type: docs
weight: 508
url: /fr/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) méthode


Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource soit terminée.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Classe [HttpWebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)