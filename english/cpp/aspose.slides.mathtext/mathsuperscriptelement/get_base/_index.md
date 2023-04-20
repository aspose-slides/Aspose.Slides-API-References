---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/mathsuperscriptelement/get_base/
---
## MathSuperscriptElement::get_Base() method


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Base() override
```

## Remarks


Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)