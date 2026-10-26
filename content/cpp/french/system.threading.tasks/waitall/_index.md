---
title: WaitAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend que tous les objets Task fournis terminent leur exécution.
type: docs
weight: 170
url: /fr/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) fonction

Attend que tous les objets [Task](../task/) fournis terminent leur exécution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un tableau d'instances [Task](../task/) sur lesquelles attendre. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) à observer pendant que l'on attend que les tasks se terminent. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) fonction

Attend que tous les objets [Task](../task/) fournis terminent leur exécution.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un tableau d'instances [Task](../task/) sur lesquelles attendre. |

## Voir aussi

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* classe [CancellationToken](../../system.threading/cancellationtoken/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)