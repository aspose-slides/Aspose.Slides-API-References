---
title: get_Superscript()
second_title: Aspose.Slides för C++ API-referens
description: Superscript-argument
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() metod


Superscript-argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)