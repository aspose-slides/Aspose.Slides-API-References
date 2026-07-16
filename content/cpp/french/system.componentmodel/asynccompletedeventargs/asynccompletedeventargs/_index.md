---
title: AsyncCompletedEventArgs()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructeur.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Initialise une nouvelle instance de la classe [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Toute erreur survenue lors de l'opération asynchrone. |
| canceled | **bool** | Une valeur indiquant si l'opération asynchrone a été annulée. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | L'objet d'état facultatif fourni par l'utilisateur passé à la méthode [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Voir aussi

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsyncCompletedEventArgs](../)
* Classe [Object](../../../system/object/)
* Espace de noms [System::ComponentModel](../../)
* Bibliothèque [Aspose.Slides](../../../)