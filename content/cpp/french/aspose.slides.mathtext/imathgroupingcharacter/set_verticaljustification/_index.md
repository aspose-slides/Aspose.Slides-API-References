---
title: set_VerticalJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom"
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) méthode

Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet tombe sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Remarques

Exemple :
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)