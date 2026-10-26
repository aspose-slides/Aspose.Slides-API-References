---
title: ConfigureAwait()
second_title: Référence de l'API Aspose.Slides pour C++
description: Configure la façon dont les attentes sur cette tâche doivent se comporter concernant la capture du contexte.
type: docs
weight: 144
url: /fr/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const méthode


Configure la façon dont les attentes sur cette tâche doivent se comporter en ce qui concerne la capture du contexte.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indique s’il faut continuer dans le contexte capturé |

### Valeur de retour

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Un objet awaitable configuré

## Voir aussi

* Classe [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Classe [Task](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)