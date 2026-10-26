---
title: operator==()
second_title: Référence de l'API Aspose.Slides pour C++
description: Opérateur d'égalité pour ResultValueTask.
type: docs
weight: 131
url: /fr/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const méthode

Opérateur d'égalité pour [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | L'autre [ResultValueTask](../) à comparer avec cette instance. |

### Valeur de retour

bool Vrai si les deux tâches ont la même valeur de résultat ou font référence à la même tâche sous-jacente ; sinon, faux.

## Remarques

Si l'une des instances contient une valeur de résultat directe, compare les résultats directement. Sinon, compare les pointeurs de tâche sous-jacents. 

## Voir aussi

* Classe [ResultValueTask](../)
* Espace de noms [System::Threading::Tasks](../../)
* Bibliothèque [Aspose.Slides](../../../)