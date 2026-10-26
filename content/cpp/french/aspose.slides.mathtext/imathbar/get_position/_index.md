---
title: get_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position de la ligne de barre. Valeur par défaut: Haut"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() méthode


Position de la ligne de barre. Valeur par défaut: Haut

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Remarques


Exemple:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)