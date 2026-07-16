---
title: get_BaseJustification()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() méthode


Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Remarques


Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Voir aussi

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)