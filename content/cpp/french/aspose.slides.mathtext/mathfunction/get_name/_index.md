---
title: get_Name()
second_title: Référence de l'API Aspose.Slides pour C++
description: Nom de la fonction Par exemple, les noms de fonctions sont sin et cos
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() méthode

Nom de la fonction Par exemple, les noms de fonctions sont sin et cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Remarques

Exemple: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)