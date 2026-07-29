---
title: get_Subscript()
second_title: Aspose.Slides för C++ API-referens
description: Subscript-argument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_subscript/
---
## IMathRightSubSuperscriptElement::get_Subscript() metod


Subscript-argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Subscript()=0
```

## Anmärkningar


Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)