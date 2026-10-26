---
title: only_load_document_properties property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties eigenschap
Deze eigenschap is zinvol als het presentatiedocument met een wachtwoord is beveiligd.
            Waarde true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiedocument en het wachtwoord moet worden genegeerd.
            Waarde false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord.
            Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd.
            Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegenereerd.
            Lezen/Schrijven **bool**.

### Definitie:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Zie ook
* klasse [`LoadOptions`](/slides/python-net/nl/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)