---
title: get_Operator()
second_title: Aspose.Slides لـ C++ مرجع API
description: "حرف عامل Nary على سبيل المثال: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() طريقة

حرف عامل Nary على سبيل المثال: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## ملاحظات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## انظر أيضاً

* الفئة [IMathNaryOperatorProperties](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)