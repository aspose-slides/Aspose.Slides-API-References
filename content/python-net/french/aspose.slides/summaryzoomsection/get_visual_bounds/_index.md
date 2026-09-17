---
title: get_visual_bounds method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

### Retour

Un **aspose.slides.RectangleF** qui représente les limites visuelles de la forme
             dans les coordonnées de la diapositive.



```python
def get_visual_bounds(self):
    ...
```


### Remarques

Le rectangle renvoyé représente les limites alignées sur les axes de tout le contenu produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive.
            
             Ces limites peuvent différer des limites du modèle de la forme
             ([`Shape.x`](/slides/python-net/fr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fr/aspose.slides/shape/height))
             et peuvent contenir des coordonnées négatives si le contenu rendu dépasse
             l'origine de la diapositive.
            
             Les limites visuelles tiennent compte des aspects liés au rendu tels que
             les transformations (par exemple, la rotation), la largeur du trait et les jointures,
             la mise en page du texte et les débordements, la géométrie SmartArt, ainsi que d'autres effets de mise en page
             qui influencent l'apparence finale rendue de la forme.
            
             Les limites renvoyées ne sont pas découpées selon le rectangle de la diapositive.



### Voir aussi
* classe [`SummaryZoomSection`](/slides/python-net/fr/aspose.slides/summaryzoomsection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)