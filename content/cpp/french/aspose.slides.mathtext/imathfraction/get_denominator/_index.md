---
title: get_Denominator()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dénominateur
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() méthode

Dénominateur

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Remarques

Exemple :
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFraction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)