---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() méthode


Argument de base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Remarques


Exemple : 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)