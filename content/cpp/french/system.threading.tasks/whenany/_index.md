---
title: WhenAny()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une tâche qui se terminera lorsque l'une des tâches fournies sera terminée.
type: docs
weight: 209
url: /fr/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) fonction

Crée une tâche qui se terminera lorsque l'une des tâches fournies sera terminée.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui représente l'achèvement de l'une des tâches fournies.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) fonction

Crée une tâche qui se terminera lorsque l'une des tâches fournies sera terminée.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui représente l'achèvement de l'une des tâches fournies.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) fonction

Crée une tâche qui se terminera lorsque l'une des tâches fournies sera terminée.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Le type du résultat de la tâche terminée. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui renvoie la première tâche terminée lorsque l'une des tâches se termine.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) fonction

Crée une tâche qui se terminera lorsque l'une des tâches fournies sera terminée.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Le type du résultat de la tâche terminée. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Les tâches à attendre pour leur achèvement. |

### Valeur de retour

Une tâche qui renvoie la première tâche terminée lorsque l'une des tâches se termine.

## Voir également

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)