---
title: get_Position()
second_title: Référence de l'API Aspose.Slides for C++
description: "Position du caractère de regroupement. Par défaut: Bottom"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() méthode

Position du caractère de regroupement. Par défaut : Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## Remarques

Exemple : 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* classe [MathGroupingCharacter](../)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)