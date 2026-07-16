---
title: ContinueWith()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une continuation qui s'exécute lorsque la tâche de résultat se termine.
type: docs
weight: 40
url: /fr/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche de résultat se termine.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action à exécuter lorsque cette tâche se termine, en recevant cette tâche de résultat |

### Valeur de retour

TaskPtr Une nouvelle tâche représentant la continuation

## Remarques

L'action de continuation reçoit ce [ResultTask](../) pour accéder à la valeur du résultat 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche de résultat se termine.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| TNewResult | Type de résultat de la continuation de la tâche |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Fonction pour obtenir le résultat de la continuation lorsque cette tâche se termine, en recevant cette tâche de résultat |

### Valeur de retour

RTaskPtr Une nouvelle tâche représentant la continuation

## Remarques

La fonction de continuation reçoit ce [ResultTask](../) pour accéder à la valeur du résultat 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche se termine.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action à exécuter lorsque cette tâche se termine |

### Valeur de retour

TaskPtr Une nouvelle tâche représentant la continuation

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) méthode

Crée une continuation qui s'exécute lorsque la tâche se termine.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| TResult | Un type de résultat de tâche |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Fonction pour obtenir le résultat lorsque cette tâche se termine |

### Valeur de retour

RTaskPtr Une nouvelle tâche représentant la continuation

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)