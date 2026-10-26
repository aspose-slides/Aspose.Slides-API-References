---
title: get_Denominator()
second_title: Référence API Aspose.Slides pour C++
description: Dénominateur
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() méthode


Dénominateur

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## Remarques


Exemple: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFraction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)