---
title: EndGetResponse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource soit terminée.
type: docs
weight: 183
url: /fr/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult>) méthode

Attend jusqu'à ce que la requête asynchrone spécifiée pour la ressource soit terminée.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)<[IAsyncResult](../../../system/iasyncresult/)> | Un [IAsyncResult](../../../system/iasyncresult/) objet qui représente une requête asynchrone pour la ressource. |

### Valeur de retour

La réponse Web.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [FileWebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)