---
title: set_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position du caractère de regroupement. Par défaut : Bottom"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) méthode


Position du caractère de regroupement. Par défaut : Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## Remarques


Exemple:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Voir aussi

* Énum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)