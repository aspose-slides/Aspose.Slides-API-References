---
title: get_Arguments()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مجموعة عناصر المصفوفة
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() طريقة

مجموعة العناصر في المصفوفة

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElementCollection](../../imathelementcollection/)
* فئة [MathArray](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)