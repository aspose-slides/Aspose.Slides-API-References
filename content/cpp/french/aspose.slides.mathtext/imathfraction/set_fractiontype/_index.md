---
title: set_FractionType()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Type de fraction Default: Bar"
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathfraction/set_fractiontype/
---
## IMathFraction::set_FractionType(MathFractionTypes) méthode

Type de fraction Par défaut: Bar

```cpp
virtual void Aspose::Slides::MathText::IMathFraction::set_FractionType(MathFractionTypes value)=0
```

## Remarques

Exemple:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathFraction->set_FractionType(MathFractionTypes::Linear);
```

## Voir aussi

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Class [IMathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)