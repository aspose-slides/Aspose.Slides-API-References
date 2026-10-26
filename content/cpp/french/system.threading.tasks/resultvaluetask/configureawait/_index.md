---
title: ConfigureAwait()
second_title: Référence de l'API Aspose.Slides pour C++
description: Configure un awaiter pour cette tâche.
type: docs
weight: 92
url: /fr/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const méthode

Configure un awaiter pour cette tâche.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true pour tenter de renvoyer la continuation au contexte d'origine capturé ; sinon, false. |

### Valeur de retour

ConfiguredResultValueTaskAwaitable<T> Un objet qui configure le comportement des awaiters pour cette tâche.

## Voir aussi

* Classe [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Classe [ResultValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)