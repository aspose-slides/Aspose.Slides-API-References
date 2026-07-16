---
title: get_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position de la ligne de barre. Par défaut : Top"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() méthode

Position de la ligne de barre. Par défaut : Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## Remarques

Exemple :
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Voir aussi

* Enumération [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathBar](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)