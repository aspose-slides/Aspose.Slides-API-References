---
title: interruption_token property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token Eigenschaft
Das Token, das auf Unterbrechungsanfragen überwacht wird.
            
            Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [`IInterruptionTokenSource.interrupt`](/slides/python-net/de/aspose.slides/iinterruptiontokensource/interrupt)-Methode des [`IInterruptionTokenSource`](/slides/python-net/de/aspose.slides/iinterruptiontokensource) unterbrochen.

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
* Klasse [`IInterruptionTokenSource`](/slides/python-net/de/aspose.slides/iinterruptiontokensource)
* Klasse [`ILoadOptions`](/slides/python-net/de/aspose.slides/iloadoptions)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)