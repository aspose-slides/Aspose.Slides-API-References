---
title: from_known_color method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Creëert een kleur van de gespecificeerde vooraf gedefinieerde kleur.<br/>Dit is de enige manier om een systeemkleur te verkrijgen (zoals `KnownColor.CONTROL`): systeemkleuren worden niet blootgesteld als `Color` attributen omdat hun waarden afhankelijk zijn van het bureaubladthema, dus ze worden uit de bibliotheekruntime gelezen.

### Retourneert

De kleur die deze methode maakt.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| known_color | **KnownColor** | Een element van de `KnownColor` enumeratie (een `IntEnum` die .NET `System.Drawing.KnownColor` nabootst) of de bijbehorende integerwaarde. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **ValueError** | De waarde is geen geldig `KnownColor` lid. |



### Zie ook
* klasse [`Color`](/slides/python-net/nl/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)