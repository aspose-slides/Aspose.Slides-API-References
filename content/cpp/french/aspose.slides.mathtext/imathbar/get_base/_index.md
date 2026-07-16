---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() méthode

Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspuse::Slides::MathText::IMathBar::get_Base()=0
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
* Classe [IMathBar](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)