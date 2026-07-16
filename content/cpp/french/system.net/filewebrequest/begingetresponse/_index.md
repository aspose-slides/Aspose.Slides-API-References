---
title: BeginGetResponse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une requête asynchrone pour la ressource.
type: docs
weight: 170
url: /fr/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) method

Initie une requête asynchrone pour la ressource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Une fonction de rappel qui sera appelée lorsque l'opération est terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)