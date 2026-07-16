---
title: InvokeCompletedEventArgs()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 14
url: /fr/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructeur


Construit une nouvelle instance.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Toute erreur qui s'est produite lors d'une opération asynchrone. |
| cancelled | **bool** | Une valeur indiquant si une opération asynchrone est annulée. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'objet d'état optionnel fourni par l'utilisateur transmis à la méthode [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Une collection de résultats d'opération asynchrone. |

## Voir aussi

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [InvokeCompletedEventArgs](../)
* Espace de noms [System::Web::Services::Protocols](../../)
* Bibliothèque [Aspose.Slides](../../../)