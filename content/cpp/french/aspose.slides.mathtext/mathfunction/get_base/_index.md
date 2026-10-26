---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de fonction
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() méthode


Argument de fonction

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Remarques


Exemple :
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)