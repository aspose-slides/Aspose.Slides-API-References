---
title: FromException()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une tâche qui s'est terminée avec une exception spécifiée.
type: docs
weight: 131
url: /fr/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) fonction

Crée une tâche qui s'est terminée avec une exception spécifiée.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | The exception with which to complete the task. |

### Valeur de retour

A faulted task.

## System::Threading::Tasks::FromException(const Exception\&) fonction


Crée une tâche qui s'est terminée avec une exception spécifiée et un type de résultat.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | The type of the task's result. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | The exception with which to complete the task. |

### Valeur de retour

A faulted task with the specified result type.

## Voir aussi

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)