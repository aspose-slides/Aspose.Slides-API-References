---
title: Yield()
second_title: Référence API Aspose.Slides for C++
description: Crée une tâche awaitable qui rend le contrôle de façon asynchrone au contexte actuel lorsqu’elle est attendue.
type: docs
weight: 222
url: /fr/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() fonction


Crée une tâche awaitable qui rend le contrôle de façon asynchrone au contexte actuel lorsqu’elle est attendue.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Valeur de retour

Un YieldAwaitable qui peut être attendu pour rendre le contrôle.
## Remarques



Cette méthode est utile pour forcer une méthode asynchrone à rendre le contrôle, permettant à d’autres travaux en attente d’être traités avant de continuer. 
## Voir aussi

* Classe [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)