---
title: interruption_token property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token eigenschap
Het token om onderbrekingsverzoeken te monitoren.

Dit token beheert de volledige levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-instantie. Elke langdurige bewerking, zoals presentatie laden of opslaan, wordt onderbroken door het aanroepen van de [`IInterruptionTokenSource.interrupt`](/slides/python-net/nl/aspose.slides/iinterruptiontokensource/interrupt)-methode van de [`IInterruptionTokenSource`](/slides/python-net/nl/aspose.slides/iinterruptiontokensource).

### Definitie:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Zie ook
* klasse [`IInterruptionTokenSource`](/slides/python-net/nl/aspose.slides/iinterruptiontokensource)
* klasse [`ILoadOptions`](/slides/python-net/nl/aspose.slides/iloadoptions)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)