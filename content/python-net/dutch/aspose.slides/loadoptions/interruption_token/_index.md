---
title: interruption_token property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token eigenschap
Het token om onderbrekingsverzoeken te monitoren.
            
            Dit token beheert de volledige levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) instantie. Elke langdurige bewerking, zoals het laden 
            of opslaan van een presentatie, wordt onderbroken door het aanroepen van de [`InterruptionTokenSource.interrupt`](/slides/python-net/nl/aspose.slides/interruptiontokensource/interrupt) methode van 
            de [`InterruptionTokenSource`](/slides/python-net/nl/aspose.slides/interruptiontokensource).

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
* klasse [`InterruptionTokenSource`](/slides/python-net/nl/aspose.slides/interruptiontokensource)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* klasse [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)