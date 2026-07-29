---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() metod


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
```

## Anmärkningar


Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathLeftSubSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)