---
title: set_Operator()
second_title: Aspose.Slides لمرجع API C++
description: "حرف المشغل Nary على سبيل المثال: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) طريقة

حرف مشغّل Nary على سبيل المثال: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## ملاحظات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## انظر أيضًا

* الفئة [IMathNaryOperatorProperties](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)