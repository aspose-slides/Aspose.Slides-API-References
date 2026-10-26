---
title: ResultTask()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un ResultTask avec une fonction qui renvoie une valeur.
type: docs
weight: 1
url: /fr/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructeur

Construit un [ResultTask](../) avec une fonction qui renvoie une valeur.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | La fonction à exécuter de manière asynchrone qui renvoie un résultat |

## ResultTask::ResultTask() constructeur

Implémentation interne. Non destiné au code utilisateur.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Remarques

Constructeur interne pour créer des tâches de résultat non initialisées

## ResultTask::ResultTask(const T\&) constructeur

Constructeur interne pour créer des tâches de résultat avec le résultat spécifié.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Voir aussi

* Classe [Func](../../../system/func/)
* Classe [ResultTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)