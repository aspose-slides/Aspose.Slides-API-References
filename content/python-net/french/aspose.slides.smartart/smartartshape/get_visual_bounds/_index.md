---
title: get_visual_bounds method
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

### Returns
Un **aspose.slides.RectangleF** qui représente les limites visuelles de la forme
             dans les coordonnées de la diapositive.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
Le rectangle retourné représente les limites alignées aux axes de tout le contenu
produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive.

Ces limites peuvent différer des limites du modèle de la forme
([`Shape.x`](/slides/python-net/fr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fr/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/fr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fr/aspose.slides/shape/height))
et peuvent contenir des coordonnées négatives si le contenu rendu dépasse
l'origine de la diapositive.

Les limites visuelles tiennent compte des aspects liés au rendu tels que
les transformations (par exemple, la rotation), la largeur du trait et les jointures,
la mise en page du texte et le dépassement, la géométrie SmartArt, ainsi que d'autres effets de mise en page qui influencent l'apparence finale rendue de la forme.

Les limites retournées ne sont pas découpées selon le rectangle de la diapositive.

### See Also
* classe [`SmartArtShape`](/slides/python-net/fr/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/fr/aspose.slides.smartart)
* bibliothèque [`Aspose.Slides`](/slides/python-net)