---
title: write_shape_start method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Appelé avant le rendu du shape. Appelé une fois pour chaque shape. Si cette fonction écrit quoi que ce soit dans generator, la génération de l'image de la diapositive actuelle sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator) | Objet de sortie. |
| shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Forme qui est sur le point d'être rendue. |

### Voir aussi
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)