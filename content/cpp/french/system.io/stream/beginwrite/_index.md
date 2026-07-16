---
title: BeginWrite()
second_title: Référence API Aspose.Slides pour C++
description: Initie une opération d'écriture asynchrone.
type: docs
weight: 170
url: /fr/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) méthode

Initie une opération d'écriture asynchrone.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tampon contenant les données à écrire |
| offset | int | Un décalage basé sur 0 dans **buffer** indiquant la position à partir de laquelle les données à écrire commencent |
| count | int | Le nombre d'octets à écrire |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Un rappel à appeler lorsque l'opération se termine |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération d'écriture asynchrone |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération d'écriture asynchrone initiée

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)