---
title: get_Base()
second_title: Référence API Aspose.Slides pour C++
description: Argument de base
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() méthode

Argument de base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Remarques

Exemple :
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathLeftSubSuperscriptElement](../)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)