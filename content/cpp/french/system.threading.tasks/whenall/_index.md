---
title: WhenAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées.
type: docs
weight: 196
url: /fr/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) fonction


Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui représente l'achèvement de toutes les tâches fournies.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) fonction


Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui représente l'achèvement de toutes les tâches fournies.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) fonction


Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Le type des résultats des tâches terminées. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui renvoie un tableau de tous les résultats lorsque toutes les tâches sont terminées.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) fonction


Crée une tâche qui se terminera lorsque toutes les tâches fournies seront terminées.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Le type des résultats des tâches terminées. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui renvoie un tableau de tous les résultats lorsque toutes les tâches sont terminées.

## Voir aussi

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)