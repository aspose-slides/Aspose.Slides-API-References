---
title: add_summary_zoom_frame method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Crée un nouveau cadre Summary Zoom et l’ajoute à la fin de la collection de formes.

### Retour
Le [`ISummaryZoomFrame`](/slides/python-net/fr/aspose.slides/isummaryzoomframe) nouvellement créé.

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Summary Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Summary Zoom, en points. |

### Remarques
Cette méthode crée un cadre Summary Zoom qui regroupe les liens de résumé pour toutes les sections de la présentation.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée s’il n’y a aucune section dans la présentation, ou si la diapositive cible n’appartient à aucune section. |

### Voir aussi
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* classe [`ISummaryZoomFrame`](/slides/python-net/fr/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)