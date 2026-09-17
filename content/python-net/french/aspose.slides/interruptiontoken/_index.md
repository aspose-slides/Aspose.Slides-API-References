---
title: InterruptionToken class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/interruptiontoken/
---
## classe InterruptionToken

Cette classe représente le jeton à utiliser pour signaler aux tâches de longue durée si l’interruption a été demandée.

Le type InterruptionToken expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`none`](/slides/python-net/fr/aspose.slides/interruptiontoken/none/) | Représente un jeton d’interruption vide.<br/>            Les opérations de longue durée ne seront jamais interrompues via [`InterruptionTokenSource.interrupt`](/slides/python-net/fr/aspose.slides/interruptiontokensource/interrupt)<br/>            lors de l’utilisation de ce jeton. |
| [`is_interruption_requested`](/slides/python-net/fr/aspose.slides/interruptiontoken/is_interruption_requested/) | Renvoie **bool**.true si l’interruption a été demandée. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/fr/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Lance une OperationCanceledException si<br/>            l’interruption a été demandée. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)