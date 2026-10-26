---
title: BeginResolve()
second_title: Référence de l'API Aspose.Slides for C++
description: Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry en utilisant le nom d'hôte spécifié.
type: docs
weight: 157
url: /fr/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) method


Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry en utilisant le nom d'hôte spécifié.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Un nom d'hôte qui est utilisé pour créer une nouvelle instance de la classe [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération se termine. |
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
* Library [Aspose.Slides](../../../)