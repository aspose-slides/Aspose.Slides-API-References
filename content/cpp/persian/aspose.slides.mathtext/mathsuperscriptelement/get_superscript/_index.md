---
title: get_Superscript()
second_title: Aspose.Slides برای C++ مرجع API
description: بالنویس
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() متد

بالنویس

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
```

## یادداشت‌ها

مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## همچنین ببینید

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathSuperscriptElement](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)