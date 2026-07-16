---
title: set_RotationAngle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est alors appliquée indépendamment de la forme. Ainsi, la forme peut recevoir une rotation en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire float.
type: docs
weight: 313
url: /fr/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) méthode

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est alors appliquée indépendamment de la forme. Ainsi, la forme peut recevoir une rotation en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Remarques

Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée à celle-ci. En plus de cela, le corps du texte lui-même a une rotation de -90 degrés dans le sens inverse des aiguilles d'une montre appliquée. Alors la forme résultante semblerait tournée, mais le texte à l'intérieur semblerait n'avoir pas été tourné du tout.

## Voir aussi

* Classe [TextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)