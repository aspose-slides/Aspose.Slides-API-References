---
title: BeginGetHostAddresses()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry à l'aide de la chaîne spécifiée contenant un nom d'hôte ou une adresse IP.
type: docs
weight: 131
url: /fr/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry à l'aide de la chaîne spécifiée contenant un nom d'hôte ou une adresse IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Une chaîne qui contient un nom d'hôte ou une adresse IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un callback qui sera appelé lorsque l'opération se termine. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)