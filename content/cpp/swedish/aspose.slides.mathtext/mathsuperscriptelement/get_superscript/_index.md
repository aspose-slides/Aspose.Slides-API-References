---
title: get_Superscript()
second_title: Aspose.Slides för C++ API-referens
description: Upphöjd
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() metod


Upphöjd

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
```

## Anmärkningar


Exempel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathSuperscriptElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)