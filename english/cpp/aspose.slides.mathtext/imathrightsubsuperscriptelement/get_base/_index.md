---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_base/
---
## IMathRightSubSuperscriptElement::get_Base() method


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Base()=0
```

## Remarks


Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)