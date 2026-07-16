---
title: TimerQueue
second_title: Référence de l'API Aspose.Slides pour C++
description: File d'attente qui gère les objets Timer. Il s'agit simplement d'une implémentation. Les objets Timer s'enregistrent eux-memes, vous n'avez pas besoin de le faire pour les utiliser - utilisez l'API de la classe Timer à la place. Il s'agit d'un type singleton dont la gestion de la mémoire est assuree par les fonctions d'accès. Vous ne devez jamais créer d'instances directement.
type: docs
weight: 261
url: /fr/system.threading/timerqueue/
---
## TimerQueue classe

File d'attente qui gère les objets [Timer](../timer/). Il s'agit simplement d'une implémentation. [Timer](../timer/) objets s'enregistrent eux-mêmes, vous n'avez pas besoin de le faire pour les utiliser – utilisez l'API de la classe [Timer](../timer/) à la place. Il s'agit d'un type singleton avec la gestion de la mémoire assurée par les fonctions d'accès. Vous ne devez jamais créer d'instances directement.

```cpp
class TimerQueue
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Enregistre le minuteur dans la file d'attente. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Supprime le minuteur de la file d'attente. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton d'implémentation. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Joint le thread de travail. Attend indéfiniment si nécessaire. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Pas de copie. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Pas de copie. |
## Voir aussi

* Espace de noms [System::Threading](../)
* Bibliothèque [Aspose.Slides](../../)