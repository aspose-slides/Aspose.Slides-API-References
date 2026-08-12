---
title: set_Operator()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) เมธอด

อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## ดูเพิ่มเติม

* คลาส [IMathNaryOperatorProperties](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)