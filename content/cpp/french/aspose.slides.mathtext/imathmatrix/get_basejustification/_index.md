---
title: get_BaseJustification()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom, et center. Valeur par défaut : Center"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() méthode

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Voir aussi

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)