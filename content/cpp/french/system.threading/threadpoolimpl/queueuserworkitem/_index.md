---
title: QueueUserWorkItem()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un élément de travail à la file d’attente.
type: docs
weight: 1
url: /fr/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) méthode

Ajoute un élément de travail à la file d’attente.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Fonction de rappel à exécuter. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument de la fonction de rappel. |

### Valeur de retour

Retourne toujours true.

## Voir aussi

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ThreadPoolImpl](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)