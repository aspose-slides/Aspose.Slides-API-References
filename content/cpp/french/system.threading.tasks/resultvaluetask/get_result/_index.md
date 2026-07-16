---
title: get_Result()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le résultat de la tâche terminée.
type: docs
weight: 66
url: /fr/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() méthode

Obtient le résultat de la tâche terminée.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Valeur de retour

T La valeur du résultat.
## Remarques


Si la tâche est prise en charge par un ResultTask<T>, cette méthode attendra le résultat et le mettra en cache. Les appels suivants renverront la valeur mise en cache sans attendre. 

## Voir aussi

* Classe [ResultValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)