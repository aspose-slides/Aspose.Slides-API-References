---
title: MathSuperscriptElement()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathSuperscriptElement class.
type: docs
weight: 27
url: /aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Initializes a new instance of the [MathSuperscriptElement](../) class.

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## Remarks


Example: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)