---
title: BeginGetRequestStream()
second_title: Référence API Aspose.Slides pour C++
description: Démarre une opération asynchrone pour obtenir un flux afin d'écrire des données dans la ressource.
type: docs
weight: 144
url: /fr/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) méthode

Démarre une opération asynchrone pour obtenir un flux afin d'écrire des données dans la ressource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un callback à appeler lorsque l'opération est terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de façon unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [FileWebRequest](../)
* Espace de noms [System::Net](../../)
* Library [Aspose.Slides](../../../)