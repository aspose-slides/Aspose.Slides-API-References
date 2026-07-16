---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de fonction
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() méthode

Argument de fonction

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Remarques

Exemple: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)