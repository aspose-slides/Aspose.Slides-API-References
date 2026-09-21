---
title: check_write_protection method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie.

### Retourwaarde

True als de presentatie schrijfbeveiligd is en het wachtwoord correct is. False anders.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | **str** | Het te controleren wachtwoord. |

### Opmerkingen

1. U moet de [`IPresentationInfo.is_write_protected`](/slides/python-net/nl/aspose.slides/ipresentationinfo/is_write_protected) eigenschap controleren voordat u deze methode aanroept.
2. Wanneer wachtwoord None of leeg is, retourneert deze methode false.

### Uitzonderingen

| Exceptie | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Zie ook
* klasse [`IPresentationInfo`](/slides/python-net/nl/aspose.slides/ipresentationinfo)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)