---
title: get_Operator()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "อักขระผู้ดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() วิธีการ

อักขระผู้ดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
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