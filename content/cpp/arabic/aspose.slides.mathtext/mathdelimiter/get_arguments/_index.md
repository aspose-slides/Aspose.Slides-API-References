---
title: get_Arguments()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: عنصر أو أكثر رياضي يتم فصله بواسطة أحرف الفاصل
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() طريقة

عنصر أو أكثر رياضي يتم فصله بواسطة أحرف الفاصل

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElementCollection](../../imathelementcollection/)
* فئة [MathDelimiter](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)