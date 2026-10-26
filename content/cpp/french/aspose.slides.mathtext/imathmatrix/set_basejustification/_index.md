---
title: set_BaseJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont haut, bas et centre. Défaut : Centre"
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) méthode

Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont haut, bas et centre. Défaut : Centre

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## Remarques

Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Voir aussi

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)