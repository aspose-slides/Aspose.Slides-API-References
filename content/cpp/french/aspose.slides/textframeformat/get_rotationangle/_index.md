---
title: get_RotationAngle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie de manière personnalisée la rotation appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation en plus de celle appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire float.
type: docs
weight: 300
url: /fr/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() méthode

Spécifie de façon personnalisée la rotation appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lire **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Remarques

Considérez le cas où une forme possède une rotation de 90 degrés dans le sens horaire appliquée. En plus de cela, le corps du texte possède une rotation de -90 degrés dans le sens anti-horaire appliquée. Alors la forme résultante apparaîtrait comme tournée, mais le texte à l’intérieur semblerait ne pas avoir été tourné du tout.

## Voir aussi

* Classe [TextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)