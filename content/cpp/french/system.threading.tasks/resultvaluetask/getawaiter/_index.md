---
title: GetAwaiter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient un awaiter pour cette tâche afin de prendre en charge les expressions await.
type: docs
weight: 118
url: /fr/system.threading.tasks/resultvaluetask/getawaiter/
---
## ResultValueTask::GetAwaiter() const méthode


Obtient un awaiter pour cette tâche afin de prendre en charge les expressions await.

```cpp
Runtime::CompilerServices::ResultValueTaskAwaiter<T> System::Threading::Tasks::ResultValueTask<T>::GetAwaiter() const
```


### Valeur de retour

ResultValueTaskAwaiter<T> Une instance d'awaiter pour cette tâche.
## Remarques



Cette méthode permet l'utilisation de la méthode Await avec [ResultValueTask](../). 

## Voir aussi

* Classe [ResultValueTaskAwaiter](../../../system.runtime.compilerservices/resultvaluetaskawaiter/)
* Classe [ResultValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)