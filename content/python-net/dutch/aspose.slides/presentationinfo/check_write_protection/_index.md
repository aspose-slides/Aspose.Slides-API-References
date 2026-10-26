---
title: check_write_protection method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie.

### Retourneert

True als de presentatie schrijfbeveiligd is en het wachtwoord correct is. False anders.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | **str** | Het wachtwoord om te controleren. |

### Opmerkingen

1. U moet de [`PresentationInfo.is_write_protected`](/slides/python-net/nl/aspose.slides/presentationinfo/is_write_protected) eigenschap controleren voordat u deze methode aanroept.
2. Wanneer wachtwoord None of leeg is, retourneert deze methode false.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Zie ook
* klasse [`PresentationInfo`](/slides/python-net/nl/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)