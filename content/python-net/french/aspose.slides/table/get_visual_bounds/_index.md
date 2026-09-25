---
title: get_visual_bounds method
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

### Retour

Un [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef) qui représente les limites visuelles de la forme
             dans les coordonnées de la diapositive.



```python
def get_visual_bounds(self):
    ...
```


### Remarques

Le rectangle retourné représente les limites alignées sur les axes de tout le contenu produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive.
            
Ces limites peuvent différer des limites du modèle de la forme
([`Shape.x`](/slides/python-net/fr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fr/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/fr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fr/aspose.slides/shape/height))
et peuvent contenir des coordonnées négatives si le contenu rendu dépasse l'origine de la diapositive.
            
Les limites visuelles prennent en compte les aspects liés au rendu tels que les transformations (par exemple, la rotation), la largeur et les jointures du trait, la mise en page du texte et le dépassement, la géométrie SmartArt, et d'autres effets de mise en page qui influencent l'apparence finale rendue de la forme.
            
Les limites retournées ne sont pas découpées selon le rectangle de la diapositive.



### Voir aussi
* classe [`Table`](/slides/python-net/fr/aspose.slides/table)
* classe [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)