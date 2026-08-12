---
title: get_Operator()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() เมธอด


อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## ดูเพิ่มเติม

* คลาส [MathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)