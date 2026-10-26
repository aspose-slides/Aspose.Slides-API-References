---
title: get_Current()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le contexte de synchronisation pour le thread actuel.
type: docs
weight: 40
url: /fr/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() méthode


Obtient le contexte de synchronisation pour le thread actuel.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Valeur de retour

SharedPtr<SynchronizationContext> Un pointeur partagé vers le contexte de synchronisation du thread actuel.
## Remarques



Renvoie null si aucun contexte de synchronisation n'a été défini pour le thread actuel. 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SynchronizationContext](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)