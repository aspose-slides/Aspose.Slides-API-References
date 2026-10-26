---
title: get_Arguments()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عنصر أو أكثر من العناصر الرياضية مفصولة بأحرف الفاصل
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() طريقة

أحد أو أكثر من العناصر الرياضية مفصولة بأحرف الفاصل

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElementCollection](../../imathelementcollection/)
* فئة [IMathDelimiter](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)