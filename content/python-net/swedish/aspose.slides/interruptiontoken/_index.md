---
title: InterruptionToken class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/interruptiontoken/
---
## InterruptionToken klass

Denna klass representerar token som används för att signalera långa körningar om avbrott har begärts.

InterruptionToken-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`none`](/slides/python-net/sv/aspose.slides/interruptiontoken/none/) | Representerar en tom avbrottstoken.<br/>            Långvariga operationer kommer aldrig att avbrytas via [`InterruptionTokenSource.interrupt`](/slides/python-net/sv/aspose.slides/interruptiontokensource/interrupt)<br/>            när denna token används. |
| [`is_interruption_requested`](/slides/python-net/sv/aspose.slides/interruptiontoken/is_interruption_requested/) | Returnerar **bool**.true om avbrott har begärts. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/sv/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Kastar ett OperationCanceledException om<br/>            avbrott har begärts. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)