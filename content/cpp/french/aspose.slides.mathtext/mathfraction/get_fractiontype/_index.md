---
title: get_FractionType()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Type de fraction Par défaut : Bar"
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathfraction/get_fractiontype/
---
## MathFraction::get_FractionType() méthode

Type de fraction Par défaut : Bar

```cpp
MathFractionTypes Aspose::Slides::MathText::MathFraction::get_FractionType() override
```

## Remarques

Exemple :
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## Voir aussi

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)