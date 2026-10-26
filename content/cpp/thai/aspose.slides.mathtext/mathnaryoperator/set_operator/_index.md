---
title: set_Operator()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อักขระ Nary Operator ตัวอย่างเช่น: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) เมธอด


อักขระ Nary Operator ตัวอย่างเช่น: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
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