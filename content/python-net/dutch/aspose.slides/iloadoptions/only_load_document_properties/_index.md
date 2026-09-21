---
title: only_load_document_properties property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties eigenschap
Deze eigenschap heeft zin als het presentiebestand met een wachtwoord beschermd is.
            Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld 
            presentiebestand en dat het wachtwoord moet worden genegeerd.
            Een waarde van false betekent dat de gehele versleutelde presentatie moet worden geladen met behulp van het juiste 
            wachtwoord.
            Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd.
            Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, 
            kunnen documenteigenschappen niet worden geladen en wordt een uitzondering gegooid.
            Lezen/schrijven **bool**.

### Definitie:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### See Also
* klasse [`ILoadOptions`](/slides/python-net/nl/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)