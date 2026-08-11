---
title: get_Operator()
second_title: مرجع API لـ Aspose.Slides للغات C++
description: "حرف المشغل Nary على سبيل المثال: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() طريقة


حرف المشغل Nary على سبيل المثال: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## ملاحظات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## انظر أيضًا

* الفئة [MathNaryOperator](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)