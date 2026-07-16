---
title: get_Base()
second_title: Référence de l'API Aspose.Slides pour C++
description: Argument de base
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() méthode


Argument de base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Remarques


Exemple:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathPhantom](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)