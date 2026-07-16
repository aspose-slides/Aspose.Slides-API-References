---
title: BeginGetHostEntry()
second_title: Référence API Aspose.Slides pour C++
description: Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry à l'aide de la chaîne spécifiée contenant un nom d'hôte ou une adresse IP.
type: docs
weight: 105
url: /fr/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry à l'aide de la chaîne spécifiée contenant un nom d'hôte ou une adresse IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | La chaîne contenant un nom d'hôte ou une adresse IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération se termine. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération asynchrone initiée.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération asynchrone pour créer une nouvelle instance de la classe IPHostEntry à l'aide de l'adresse IP spécifiée.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'adresse IP. |
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
* Classe [IPAddress](../../ipaddress/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)