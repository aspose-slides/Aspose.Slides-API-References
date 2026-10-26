---
title: Cancel()
second_title: Référence de l'API Aspose.Slides for C++
description: Communique une demande d'annulation.
type: docs
weight: 40
url: /fr/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() méthode


Communique une demande d'annulation.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Remarques



Tous les rappels enregistrés seront invoqués. 

Les appels suivants à [get_IsCancellationRequested()](../get_iscancellationrequested/) renverront true. 

Les rappels sont exécutés de manière synchrone pendant cet appel. 

## Voir aussi

* Classe [CancellationTokenSource](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)