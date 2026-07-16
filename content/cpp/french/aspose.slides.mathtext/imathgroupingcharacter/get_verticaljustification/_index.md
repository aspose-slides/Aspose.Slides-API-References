---
title: get_VerticalJustification()
second_title: Référence API Aspose.Slides for C++
description: "Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base. Valeur par défaut: Bottom pour Position=Top et Top pour Position=Bottom"
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() méthode

Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base. Valeur par défaut : Bottom pour Position=Top et Top pour Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Remarques


Exemple:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* classe [IMathGroupingCharacter](../)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)