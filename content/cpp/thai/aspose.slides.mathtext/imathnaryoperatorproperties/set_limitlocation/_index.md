---
title: set_LimitLocation()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) เมธอด


ตำแหน่งของลิมิต (ตัวห้อยและตัวยก)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
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