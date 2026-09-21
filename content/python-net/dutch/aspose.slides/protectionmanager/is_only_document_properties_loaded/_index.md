---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded eigenschap
Deze eigenschap heeft zin, als het presentatiedocument met een wachtwoord beschermd is en de documenteigenschappen van dit bestand openbaar zijn.
Waarde true betekent dat alleen documenteigenschappen worden geladen uit een versleuteld presentatiedocument zonder gebruik van een wachtwoord.
Waarde false betekent dat de volledige versleutelde presentatie wordt geladen met gebruik van het juiste wachtwoord, niet alleen documenteigenschappen worden geladen.
Als de presentatie niet versleuteld is, is de eigenschapswaarde altijd false.
Als documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschapswaarde altijd false.
Als Presentation.EncryptDocumentProperties true is, dan is de IsOnlyDocumentPropertiesLoaded eigenschapwaarde altijd false.
Alleen-lezen **bool**.

### Definitie:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Zie ook
* klasse [`ProtectionManager`](/slides/python-net/nl/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)