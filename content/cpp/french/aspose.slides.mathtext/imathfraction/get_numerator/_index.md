---
title: get_Numerator()
second_title: Référence de l'API Aspose.Slides pour C++
description: Numérateur
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() méthode


Numérateur

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
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
* Classe [IMathFraction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)