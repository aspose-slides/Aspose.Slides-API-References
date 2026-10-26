---
title: BeginRead()
second_title: Référence de l'API Aspose.Slides for C++
description: Initie une opération de lecture asynchrone.
type: docs
weight: 157
url: /fr/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) méthode

Initie une opération de lecture asynchrone.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tampon où lire |
| offset | int | Un décalage basé sur 0 dans **buffer** indiquant la position à partir de laquelle commencer à écrire les données lues |
| count | int | Le nombre d'octets à lire |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Un rappel à appeler lorsque l'opération se termine |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de lecture asynchrone |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de lecture asynchrone initiée

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)