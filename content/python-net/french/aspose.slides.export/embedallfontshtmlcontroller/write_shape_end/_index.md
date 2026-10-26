---
title: write_shape_end method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.


```python
def write_shape_end(self, generator, shape):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator) | Objet de sortie. |
| shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Forme rendue en dernier. |



### Voir aussi
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)