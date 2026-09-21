---
title: InterruptionToken class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/interruptiontoken/
---
## InterruptionToken klasse

Deze klasse vertegenwoordigt het token dat gebruikt wordt om lange taken te signaleren of de onderbreking is aangevraagd.

Het InterruptionToken type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`none`](/slides/python-net/nl/aspose.slides/interruptiontoken/none/) | Stelt een leeg onderbrekingstoken voor.<br/>            Langdurige taken worden nooit onderbroken via [`InterruptionTokenSource.interrupt`](/slides/python-net/nl/aspose.slides/interruptiontokensource/interrupt)<br/>            bij gebruik van dit token. |
| [`is_interruption_requested`](/slides/python-net/nl/aspose.slides/interruptiontoken/is_interruption_requested/) | Retourneert **bool**.true als onderbreking is aangevraagd. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/nl/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Gooit een OperationCanceledException indien<br/>            onderbreking is aangevraagd. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)