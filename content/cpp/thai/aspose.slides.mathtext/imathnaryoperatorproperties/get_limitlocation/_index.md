---
title: get_LimitLocation()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() เมธอด

ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## ดูเพิ่มเติม

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)