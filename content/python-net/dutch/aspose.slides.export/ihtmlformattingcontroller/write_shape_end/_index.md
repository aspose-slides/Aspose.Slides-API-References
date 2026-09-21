---
title: write_shape_end method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Wordt aangeroepen vóór het renderen van de vorm. Wordt één keer per elke vorm aangeroepen. Als deze functie iets naar de generator schrijft, wordt de huidige dia-afbeeldingsgeneratie voltooid, het toegevoegde html-fragment ingevoegd en wordt een nieuwe afbeelding bovenop de vorige gestart.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/nl/aspose.slides.export/ihtmlgenerator) | Uitvoerobject. |
| shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | Vorm die als laatste wordt gerenderd. |

### Zie ook
* klasse [`IHtmlFormattingController`](/slides/python-net/nl/aspose.slides.export/ihtmlformattingcontroller)
* klasse [`IHtmlGenerator`](/slides/python-net/nl/aspose.slides.export/ihtmlgenerator)
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)