---
title: get_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position du caractère de groupement. Par défaut : Bas"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() méthode

Position du caractère de groupement. Par défaut : Bas

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Remarques


Exemple :
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)