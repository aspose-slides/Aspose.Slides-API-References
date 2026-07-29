---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_base/
---
## IMathRightSubSuperscriptElement::get_Base() metod


Basargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Base()=0
```

## Anmärkningar


Exempel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathRightSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)