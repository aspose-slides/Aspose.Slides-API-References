---
title: BeginGetHostByName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry en utilisant le nom d'hôte spécifié.
type: docs
weight: 53
url: /fr/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération asynchrone pour créer une instance de la classe IPHostEntry à l'aide du nom d'hôte spécifié.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Un nom d'hôte. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération sera terminée. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [Dns](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)