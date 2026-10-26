---
title: get_RotationAngle()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation du texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire float.
type: docs
weight: 339
url: /fr/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() méthode

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation du texte lui-même. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```
## Remarques

Considérez le cas où une forme possède une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. En plus de cela, le corps du texte lui-même possède une rotation de -90 degrés dans le sens inverse des aiguilles d'une montre appliquée. Alors la forme résultante semblerait être tournée, mais le texte à l'intérieur apparaîtrait comme s'il n'avait pas du tout été tourné.

## Voir aussi

* Classe [ITextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)