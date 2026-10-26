---
title: GetAwaiter()
second_title: Référence API Aspose.Slides pour C++
description: Obtient un awaiter pour cette tâche de résultat à utiliser avec Await.
type: docs
weight: 53
url: /fr/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const méthode


Obtient un awaiter pour cette tâche de résultat à utiliser avec Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Valeur de retour

Runtime::CompilerServices::ResultTaskAwaiter<T> Une instance awaiter qui renvoie le résultat
## Remarques

Lorsqu'il est awaited, la coroutine reprendra avec la valeur du résultat disponible

## Voir aussi

* Classe [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Classe [ResultTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)