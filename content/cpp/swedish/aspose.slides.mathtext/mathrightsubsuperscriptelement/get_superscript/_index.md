---
title: get_Superscript()
second_title: Aspose.Slides för C++ API-referens
description: Superscript-argument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_superscript/
---
## MathRightSubSuperscriptElement::get_Superscript() metod


Superscript argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Superscript() override
```

## Anmärkningar


Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IMathElement](../../imathelement/)
* klass [MathRightSubSuperscriptElement](../)
* namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)