---
title: GetVisualBounds()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.
type: docs
weight: 677
url: /fr/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() méthode


Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Valeur de retour

Un [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) qui représente les limites visuelles de la forme dans les coordonnées de la diapositive.
## Remarques


Le rectangle retourné représente les limites alignées sur les axes de tout le contenu produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive.

Ces limites peuvent différer des limites du modèle de la forme ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) et peuvent contenir des coordonnées négatives si le contenu rendu dépasse l'origine de la diapositive.

Les limites visuelles tiennent compte des aspects liés au rendu tels que les transformations (par exemple, la rotation), la largeur et les jointures du trait, la mise en page du texte et le débordement, la géométrie [SmartArt](../../../aspose.slides.smartart/), et d'autres effets de mise en page qui influencent l'apparence finale rendue de la forme.

Les limites retournées ne sont pas découpées selon le rectangle de la diapositive. 

## Voir aussi

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Shape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)