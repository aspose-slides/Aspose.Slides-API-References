---
title: ContinueWith()
second_title: Aspose.Slides pour C++ Référence API
description: Crée une continuation qui s'exécute lorsque la tâche se termine.
type: docs
weight: 118
url: /fr/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche est terminée.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action à exécuter lorsque cette tâche se termine |

### Valeur de retour

TaskPtr Une nouvelle tâche représentant la continuation

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche est terminée.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Un type de résultat de tâche |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Fonction pour obtenir le résultat lorsque cette tâche se termine |

### Valeur de retour

RTaskPtr Une nouvelle tâche représentant la continuation

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)