---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides للغة C++ مرجع API
description: حرف المشغل ينمو رأسياً ليتطابق مع ارتفاع المعامل
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) طريقة

يتوسع حرف المشغل رأسياً ليتطابق مع ارتفاع المعامل الخاص به

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## ملاحظات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## انظر أيضا

* فئة [IMathNaryOperatorProperties](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)