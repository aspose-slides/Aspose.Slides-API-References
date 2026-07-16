---
title: set_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position du caractère de regroupement. Valeur par défaut: Bottom"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/set_position/
---
## MathGroupingCharacter::set_Position(MathTopBotPositions) méthode


Position du caractère de regroupement. Valeur par défaut: Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Position(MathTopBotPositions value) override
```

## Remarques


Exemple :
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Voir aussi

* Énum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)