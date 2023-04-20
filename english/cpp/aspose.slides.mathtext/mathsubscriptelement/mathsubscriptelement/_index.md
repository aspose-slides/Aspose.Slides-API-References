---
title: MathSubscriptElement()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathSubscriptElement class.
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Initializes a new instance of the [MathSubscriptElement](../) class.

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Remarks


Example: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathSubscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)