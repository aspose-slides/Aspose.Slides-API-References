---
title: set_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Position de la ligne de la barre. Par défaut: Top"
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathbar/set_position/
---
## IMathBar::set_Position(MathTopBotPositions) méthode

Position de la ligne de la barre. Par défaut : Top

```cpp
virtual void Aspose::Slides::MathText::IMathBar::set_Position(MathTopBotPositions value)=0
```

## Remarques

Exemple :

```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Voir aussi

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathBar](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)