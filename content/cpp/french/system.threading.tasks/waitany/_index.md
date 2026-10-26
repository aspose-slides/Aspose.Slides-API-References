---
title: WaitAny()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend que l'un des objets Task fournis termine son exécution.
type: docs
weight: 183
url: /fr/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) fonction


Attend que l'un des objets [Task](../task/) fournis termine son exécution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un tableau d'instances [Task](../task/) sur lequel attendre. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) à observer pendant l'attente de la fin des tâches. |

### Valeur de retour

L’index de la tâche terminée dans le tableau des tâches.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) fonction


Attend que l'un des objets [Task](../task/) fournis termine son exécution.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un tableau d'instances [Task](../task/) sur lequel attendre. |

### Valeur de retour

L’index de la tâche terminée dans le tableau des tâches.

## Voir aussi

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)