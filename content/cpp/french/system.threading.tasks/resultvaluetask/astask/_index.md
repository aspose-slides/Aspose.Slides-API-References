---
title: AsTask()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit ce ResultValueTask en un pointeur partagé vers ResultTask<T>.
type: docs
weight: 79
url: /fr/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const méthode


Convertit ce [ResultValueTask](../) en un pointeur partagé vers ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Valeur de retour

RTaskPtr<T> Un pointeur partagé vers ResultTask<T> qui représente cette opération.
## Remarques



Si le [ResultValueTask](../) contient un résultat direct, crée une tâche terminée avec ce résultat. S'il contient une tâche, renvoie un pointeur partagé vers cette tâche. 

## Voir aussi

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)