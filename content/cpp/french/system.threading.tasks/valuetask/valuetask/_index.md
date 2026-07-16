---
title: ValueTask()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un ValueTask vide et non initialisé.
type: docs
weight: 1
url: /fr/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructeur

Construit un [ValueTask](../) vide et non initialisé.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Remarques

La tâche n’est pas terminée et ne contient aucun résultat. Tenter d’obtenir le résultat déclenchera une exception.

## ValueTask::ValueTask(const TaskPtr\&) constructeur

Construit un [ValueTask](../) à partir d'un pointeur partagé vers un [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | La tâche à encapsuler. Peut être null pour une tâche vide. |

## Remarques

[ValueTask](../) représentera l’état de la tâche fournie.

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [ValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)