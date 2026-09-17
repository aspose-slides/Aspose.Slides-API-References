---
title: get_visual_bounds method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

### Valeur de retour

Un **aspose.slides.RectangleF** qui représente les limites visuelles de la forme
             dans les coordonnées de la diapositive.



```python
def get_visual_bounds(self):
    ...
```


### Remarques

Le rectangle retourné représente les limites alignées sur les axes de tout le contenu
             produit par la forme lors du rendu dans l'espace des coordonnées de la diapositive.
            
             Ces limites peuvent différer des limites du modèle de la forme
             ([`Shape.x`](/slides/python-net/fr/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fr/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fr/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fr/aspose.slides/shape/height))
             et peuvent contenir des coordonnées négatives si le contenu rendu dépasse
             l'origine de la diapositive.
            
             Les limites visuelles tiennent compte des aspects liés au rendu tels que
             les transformations (par exemple, la rotation), la largeur et les jointures des traits,
             la mise en page du texte et le dépassement, la géométrie SmartArt, et d'autres effets de mise en page
             qui influencent l'apparence finale rendue de la forme.
            
             Les limites retournées ne sont pas découpées au rectangle de la diapositive.



### Voir aussi
* classe [`Ink`](/slides/python-net/fr/aspose.slides.ink/ink)
* module [`aspose.slides.ink`](/slides/python-net/fr/aspose.slides.ink)
* bibliothèque [`Aspose.Slides`](/slides/python-net)