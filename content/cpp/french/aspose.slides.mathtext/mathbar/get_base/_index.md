---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument Base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() méthode

Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Remarques

Exemple :
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBar](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)