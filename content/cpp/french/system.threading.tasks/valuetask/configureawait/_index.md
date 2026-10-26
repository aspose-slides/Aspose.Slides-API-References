---
title: ConfigureAwait()
second_title: Référence de l'API Aspose.Slides pour C++
description: Configure un awaiter pour cette tâche.
type: docs
weight: 79
url: /fr/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const méthode


Configure un awaiter pour cette tâche.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true pour tenter de transférer la continuation vers le contexte original capturé ; sinon, false. |

### Valeur de retour

ConfiguredValueTaskAwaitable Un objet qui configure le comportement des awaiters pour cette tâche.

## Voir également

* Classe [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Classe [ValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)