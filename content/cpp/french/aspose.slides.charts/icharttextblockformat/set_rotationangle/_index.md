---
title: set_RotationAngle()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est alors appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire float."
type: docs
weight: 248
url: /fr/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) méthode

Spécifie la rotation personnalisée qui est appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est alors appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical pré-défini dans la propriété TextVerticalType. Écrire **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Remarques

Considérez le cas où une forme possède une rotation de 90 degrés dans le sens horaire qui lui est appliquée. En plus de cela, le corps du texte lui-même a une rotation de -90 degrés dans le sens antihoraire qui lui est appliquée. Alors, la forme résultante semblerait être tournée mais le texte à l'intérieur semblerait ne pas avoir été tourné du tout. 

## Voir aussi

* Classe [IChartTextBlockFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)