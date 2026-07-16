---
title: FromCanceled()
second_title: Référence API Aspose.Slides pour C++
description: Crée une tâche qui s'est terminée en raison d'une annulation avec le jeton spécifié.
type: docs
weight: 118
url: /fr/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) fonction

Crée une tâche qui s'est terminée en raison d'une annulation avec le jeton spécifié.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Le jeton d'annulation qui a entraîné l'annulation de la tâche. |

### Valeur de retour

Une tâche annulée.

## Voir aussi

* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)