---
title: get_Subscript()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Argument dolního indexu
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_subscript/
---
## MathRightSubSuperscriptElement::get_Subscript() metoda


Argument dolního indexu

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Subscript() override
```

## Poznámky


Příklad:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathRightSubSuperscriptElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)