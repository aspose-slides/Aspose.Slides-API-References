---
title: get_Subscript()
second_title: Aspose.Slides pro C++ – reference API
description: Dolní index
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() metoda


Dolní index

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## Poznámky


Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathLeftSubSuperscriptElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)