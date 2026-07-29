---
title: get_Subscript()
second_title: Aspose.Slides för C++ API-referens
description: Nedsänkt
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() metod

Nedsänkt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## Anmärkningar

Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathLeftSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)