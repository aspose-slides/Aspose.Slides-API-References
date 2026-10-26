---
title: ResultValueTask()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un ResultValueTask vide et non initialisé.
type: docs
weight: 1
url: /fr/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructeur

Construit un [ResultValueTask](../) vide et non initialisé.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Remarques

La tâche n'est pas terminée et ne contient aucun résultat. Tenter d'obtenir le résultat lèvera une exception.

## ResultValueTask::ResultValueTask(const T\&) constructeur

Construit un [ResultValueTask](../) terminé avec le résultat spécifié.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| result | const T\& | La valeur du résultat à encapsuler dans une tâche terminée. |

## Remarques

Cela crée une tâche réussie terminée qui renvoie immédiatement la valeur.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructeur

Construit un [ResultValueTask](../) à partir d'un pointeur partagé vers un ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | La tâche à encapsuler. Peut être null pour une tâche vide. |

## Remarques

Le [ResultValueTask](../) représentera l'état et le résultat de la tâche fournie.

## Voir aussi

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)