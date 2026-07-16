---
title: CancellationTokenRegistration
second_title: Référence API Aspose.Slides pour C++
description: Représente un enregistrement pour un rappel de jeton d'annulation.
type: docs
weight: 27
url: /fr/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration classe

Représente un enregistrement pour un rappel de jeton d'annulation.

```cpp
class CancellationTokenRegistration
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Dispose](./dispose/)() | Libère l'enregistrement et supprime le rappel du [CancellationTokenSource](../cancellationtokensource/) associé. Après avoir appelé cette méthode, le rappel enregistré ne sera plus invoqué lorsque le [CancellationTokenSource](../cancellationtokensource/) associé sera annulé. |

## Remarques

Cette classe permet la désinscription d'un rappel d'un jeton d'annulation. Lorsqu'elle est libérée, elle supprime le rappel du [CancellationTokenSource](../cancellationtokensource/) associé.  
Cette classe ne doit pas être créée directement - elle est renvoyée par les méthodes d'enregistrement [CancellationToken](../cancellationtoken/). 

## Voir aussi

* Espace de noms [System::Threading](../)
* Bibliothèque [Aspose.Slides](../../)