---
title: set_LimitLocation()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) เมธอด

ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## ดูเพิ่มเติม

* Enum [MathLimitLocations](../../mathlimitlocations/)
* คลาส [MathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)