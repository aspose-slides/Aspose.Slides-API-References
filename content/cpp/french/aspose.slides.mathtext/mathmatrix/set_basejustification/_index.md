---
title: set_BaseJustification()
second_title: Référence API Aspose.Slides pour C++
description: "Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center"
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) méthode

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Voir aussi

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)