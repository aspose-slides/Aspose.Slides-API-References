---
title: get_Base()
second_title: Référence API Aspose.Slides pour C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() méthode


Argument de base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Remarques


Exemple:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)