---
title: get_Name()
second_title: Référence de l'API Aspose.Slides pour C++
description: Nom de fonction Par exemple, les noms de fonctions sont sin et cos
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() méthode

Nom de fonction Par exemple, les noms de fonctions sont sin et cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Remarques

Exemple :
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunction](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)