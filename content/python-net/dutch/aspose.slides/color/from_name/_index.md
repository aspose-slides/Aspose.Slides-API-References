---
title: from_name method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Maakt een kleur aan van de opgegeven naam van een vooraf gedefinieerde kleur.<br/>De zoekopdracht is hoofdletterongevoelig en negeert onderstrepingstekens en spaties: `"LightBlue"`, `"lightblue"` en `"light_blue"` lossen allemaal op in `Color.light_blue`. Zie de [`Color`](/slides/python-net/nl/aspose.slides/color) klasse-pagina voor de lijst met vooraf gedefinieerde kleuren.

### Retour
De benoemde kleur.

```python
@staticmethod
def from_name(name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | **str** | Een tekenreeks die de naam van een vooraf gedefinieerde kleur is. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **ValueError** | De naam is geen naam van een vooraf gedefinieerde kleur. |
| **TypeError** | De naam is geen tekenreeks. |

### Zie ook
* klasse [`Color`](/slides/python-net/nl/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)