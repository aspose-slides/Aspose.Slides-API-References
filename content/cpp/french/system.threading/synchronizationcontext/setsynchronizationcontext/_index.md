---
title: SetSynchronizationContext()
second_title: Référence API Aspose.Slides pour C++
description: Définit le contexte de synchronisation pour le thread actuel.
type: docs
weight: 53
url: /fr/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) méthode

Définit le contexte de synchronisation pour le thread actuel.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Le contexte de synchronisation à définir pour le thread actuel. |

## Remarques

Passer nullptr effacera le contexte de synchronisation pour le thread actuel. 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SynchronizationContext](../)
* Espace de noms [System::Threading](../../)
* Library [Aspose.Slides](../../../)