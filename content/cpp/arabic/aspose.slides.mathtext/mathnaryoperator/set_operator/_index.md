---
title: set_Operator()
second_title: Aspose.Slides لـ C++ مرجع API
description: "حرف المشغل Nary على سبيل المثال: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) طريقة

حرف المشغل Nary على سبيل المثال: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```
## ملاحظات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```
## انظر أيضًا

* فئة [MathNaryOperator](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)