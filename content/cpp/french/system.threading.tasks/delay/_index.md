---
title: Delay()
second_title: Référence API Aspose.Slides pour C++
description: Crée une tâche qui se termine après un délai.
type: docs
weight: 105
url: /fr/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) fonction

Crée une tâche qui se termine après un délai.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Le nombre de millisecondes à attendre avant de terminer la tâche renvoyée, ou -1 pour attendre indéfiniment. |

### Valeur de retour

Une tâche qui représente le délai.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) fonction

Crée une tâche qui se termine après un délai et peut être annulée.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Le nombre de millisecondes à attendre avant de terminer la tâche renvoyée, ou -1 pour attendre indéfiniment. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Le jeton d'annulation qui peut être utilisé pour annuler le délai. |

### Valeur de retour

Une tâche qui représente le délai.

## Voir aussi

* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)