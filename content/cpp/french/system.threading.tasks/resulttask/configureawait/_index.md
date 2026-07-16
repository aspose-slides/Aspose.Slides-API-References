---
title: ConfigureAwait()
second_title: Référence de l'API Aspose.Slides for C++
description: Configure la façon dont les attentes sur cette tâche de résultat doivent se comporter concernant la capture du contexte.
type: docs
weight: 27
url: /fr/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const method


Configure la façon dont les attentes sur cette tâche de résultat doivent se comporter concernant la capture du contexte.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indique s'il faut continuer sur le contexte capturé |

### Valeur de retour

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Un awaitable configuré pour le résultat

## Remarques

Cela permet un contrôle granulaire du flux de contexte pour les modèles async/await

## See Also

* Classe [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Classe [ResultTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)