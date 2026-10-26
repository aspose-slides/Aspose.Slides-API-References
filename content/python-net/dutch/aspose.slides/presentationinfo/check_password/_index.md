---
title: check_password method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Controleert of een wachtwoord correct is voor een presentatie die beschermd is met een open wachtwoord.

### Retour

True als de presentatie beschermd is met een open wachtwoord en het wachtwoord correct is, anders false.



```python
def check_password(self, password):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | **str** | Het te controleren wachtwoord. |

### Opmerkingen

Wanneer het wachtwoord None of leeg is, geeft deze methode false terug.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Zie ook
* klasse [`PresentationInfo`](/slides/python-net/nl/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)