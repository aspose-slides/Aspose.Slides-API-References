---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Crée un nouveau cadre Summary Zoom et l'insère dans la collection de formes à l'index spécifié.

### Retour
Le [`ISummaryZoomFrame`](/slides/python-net/fr/aspose.slides/isummaryzoomframe) nouvellement créé.



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro auquel insérer le cadre Summary Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Summary Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Summary Zoom, en points. |

### Remarques
Cette méthode crée un cadre Summary Zoom qui regroupe les liens de résumé pour toutes les sections de la présentation.

### Exceptions
| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si la présentation ne contient aucune section, ou si la diapositive cible n'appartient à aucune section. |



### Voir aussi
* classe [`ISummaryZoomFrame`](/slides/python-net/fr/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)