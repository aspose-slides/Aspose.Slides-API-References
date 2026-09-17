---
title: get_visual_bounds method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.ink/inkactions/get_visual_bounds/
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

Le rectangle retourné représente les limites alignées sur les axes de tout le contenu
             produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive.

Ces limites peuvent différer des limites du modèle de la forme
             ([`Shape.x`](/slides/python-net/fr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fr/aspose.slides/shape/height))
             et peuvent contenir des coordonnées négatives si le contenu rendu dépasse
             l'origine de la diapositive.

Les limites visuelles tiennent compte des aspects liés au rendu tels que
             les transformations (par exemple, la rotation), la largeur du trait et les jointures,
             la mise en page du texte et les débordements, la géométrie SmartArt, et d'autres effets de mise en page
             qui influencent l'apparence finale rendue de la forme.

Les limites retournées ne sont pas découpées selon le rectangle de la diapositive.



### Voir aussi
* classe [`InkActions`](/slides/python-net/fr/aspose.slides.ink/inkactions)
* module [`aspose.slides.ink`](/slides/python-net/fr/aspose.slides.ink)
* bibliothèque [`Aspose.Slides`](/slides/python-net)