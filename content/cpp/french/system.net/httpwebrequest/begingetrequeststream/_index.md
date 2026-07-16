---
title: BeginGetRequestStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération asynchrone pour obtenir un flux afin d'écrire des données vers la ressource.
type: docs
weight: 469
url: /fr/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération asynchrone pour obtenir un flux afin d'écrire des données vers la ressource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un rappel à appeler lorsque l'opération se termine. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de façon unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [HttpWebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)