---
title: InterruptionToken class
second_title: Aspose.Slides für Python über die .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/interruptiontoken/
---
## InterruptionToken Klasse

Diese Klasse repräsentiert das Token, das verwendet wird, um langen Aufgaben mitzuteilen, ob eine Unterbrechung angefordert wurde.

Der Typ InterruptionToken stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`none`](/slides/python-net/de/aspose.slides/interruptiontoken/none/) | Stellt ein leeres Unterbrechungs-Token dar.<br/>            Langlaufende Vorgänge werden niemals über [`InterruptionTokenSource.interrupt`](/slides/python-net/de/aspose.slides/interruptiontokensource/interrupt) unterbrochen,<br/>            wenn dieses Token verwendet wird. |
| [`is_interruption_requested`](/slides/python-net/de/aspose.slides/interruptiontoken/is_interruption_requested/) | Gibt **bool**.true zurück, wenn eine Unterbrechung angefordert wurde. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/de/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Wirft eine OperationCanceledException, wenn<br/>            eine Unterbrechung angefordert wurde. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)