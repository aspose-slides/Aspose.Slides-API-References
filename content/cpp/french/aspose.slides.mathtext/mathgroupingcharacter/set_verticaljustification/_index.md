---
title: set_VerticalJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe se trouve au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base. Par défaut : Bottom pour Position=Top, et Top pour Position=Bottom"
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) méthode

Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe se trouve au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base. Par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Remarques

Exemple :
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Voir aussi

* Énum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)