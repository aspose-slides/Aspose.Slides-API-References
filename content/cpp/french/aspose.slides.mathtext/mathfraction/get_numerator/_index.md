---
title: get_Numerator()
second_title: Référence API Aspose.Slides pour C++
description: Numérateur
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() méthode


Numérateur

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## Remarques


Exemple: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFraction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)