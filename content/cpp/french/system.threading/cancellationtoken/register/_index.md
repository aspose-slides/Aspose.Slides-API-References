---
title: Register()
second_title: Référence de l'API Aspose.Slides pour C++
description: Enregistre un rappel qui sera invoqué lorsque l'annulation est demandée.
type: docs
weight: 40
url: /fr/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const méthode

Enregistre un rappel qui sera invoqué lorsque l'annulation est demandée.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | L'Action<> à exécuter lorsque l'annulation est demandée. |

### Valeur de retour

Un objet [CancellationTokenRegistration](../../cancellationtokenregistration/) qui peut être utilisé pour désenregistrer le rappel.

## Remarques

Si l'annulation a déjà été demandée, le rappel sera invoqué immédiatement.  

Le rappel doit être de courte durée et non bloquant, car il sera exécuté sur le thread qui appelle Cancel() sur le [CancellationTokenSource](../../cancellationtokensource/).

## Voir aussi

* Typedef [Action](../../../system/action/)
* Classe [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Classe [CancellationToken](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)