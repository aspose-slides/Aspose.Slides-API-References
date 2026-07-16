---
title: Run()
second_title: Référence de l'API Aspose.Slides pour C++
description: Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un handle Task pour ce travail.
type: docs
weight: 157
url: /fr/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) fonction

Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un [Task](../task/) handle pour ce travail.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Le travail à exécuter de manière asynchrone. |

### Valeur de retour

Un [Task](../task/) qui représente le travail mis en file d'attente pour s'exécuter dans le pool de threads.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) fonction

Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un [Task](../task/) handle pour ce travail.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Le travail à exécuter de manière asynchrone. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un jeton d'annulation qui peut être utilisé pour annuler le travail s'il n'a pas encore commencé. |

### Valeur de retour

Un [Task](../task/) qui représente le travail mis en file d'attente pour s'exécuter dans le pool de threads.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) fonction

Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un proxy pour le [Task](../task/) renvoyé par la fonction.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Le travail à exécuter de manière asynchrone, qui renvoie un [Task](../task/). |

### Valeur de retour

Un [Task](../task/) qui représente un proxy pour le [Task](../task/) renvoyé par la fonction.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) fonction

Met en file d'attente le travail spécifié pour s'exécuter dans le pool de threads et renvoie un handle Task<TResult> pour ce travail.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TResult | Le type du résultat renvoyé par la tâche. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Le travail à exécuter de manière asynchrone. |

### Valeur de retour

Une Task<TResult> qui représente le travail mis en file d'attente pour s'exécuter dans le pool de threads.

## Voir aussi

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Classe [Func](../../system/func/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)