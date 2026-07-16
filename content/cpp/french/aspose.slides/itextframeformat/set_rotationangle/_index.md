---
title: set_RotationAngle()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire float.
type: docs
weight: 352
url: /fr/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) méthode


Spécifie la rotation personnalisée qui est appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, alors elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Écrire **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Remarques


Considérez le cas où une forme possède une rotation de 90 degrés dans le sens horaire appliquée à celle-ci. En plus de cela, le corps du texte lui-même a une rotation de -90 degrés dans le sens antihoraire appliquée à celui-ci. Alors la forme résultante semblerait être tournée mais le texte qu’elle contient apparaîtrait comme s’il n’avait pas du tout été tourné.

## Voir aussi

* Classe [ITextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)