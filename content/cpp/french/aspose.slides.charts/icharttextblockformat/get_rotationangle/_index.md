---
title: get_RotationAngle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire float.
type: docs
weight: 235
url: /fr/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() méthode

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la zone de délimitation. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Remarques

Considérez le cas où une forme possède une rotation de 90 degrés dans le sens horaire appliquée. En plus de cela, le corps du texte lui-même a une rotation de -90 degrés dans le sens antihoraire appliquée. Alors la forme résultante semblerait être tournée mais le texte à l'intérieur apparaîtrait comme s'il n'avait pas du tout été tourné.

## Voir aussi

* Classe [IChartTextBlockFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)