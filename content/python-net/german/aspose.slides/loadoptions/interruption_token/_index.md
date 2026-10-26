---
title: interruption_token property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token Eigenschaft
Das Token zur Überwachung von Unterbrechungsanfragen.

            Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) Instanz. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [`InterruptionTokenSource.interrupt`](/slides/python-net/de/aspose.slides/interruptiontokensource/interrupt) Methode des [`InterruptionTokenSource`](/slides/python-net/de/aspose.slides/interruptiontokensource) unterbrochen.

### Definition:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Siehe auch
* Klasse [`InterruptionTokenSource`](/slides/python-net/de/aspose.slides/interruptiontokensource)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Klasse [`LoadOptions`](/slides/python-net/de/aspose.slides/loadoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)