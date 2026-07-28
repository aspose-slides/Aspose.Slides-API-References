---
title: MathSubscriptElement()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre a MathSubscriptElement osztályból.
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Új példányt hoz létre a [MathSubscriptElement](../) osztályból.

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathSubscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)