---
title: get_LimitLocation()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตำแหน่งของลิมิต (ซับสคริปต์และซูเปอร์สคริปต์)
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() เมธอด


ตำแหน่งของลิมิต (ซับสคริปต์และซูเปอร์สคริปต์)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
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
* ไลบรารี [Aspose.Slides](../../../)