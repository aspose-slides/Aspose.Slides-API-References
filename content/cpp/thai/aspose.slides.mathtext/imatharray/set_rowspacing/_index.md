---
title: set_RowSpacing()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "การเว้นระยะระหว่างแถวของอาเรย์ ใช้ได้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 เมื่อเป็น Exact หน่วยวัดคือ points หรือเมื่อเป็น Multiple หน่วยวัดคือ half-lines. ค่าเริ่มต้น: 0"
type: docs
weight: 131
url: /th/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) เมธอด

การเว้นระยะระหว่างแถวของอาเรย์ ใช้ได้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 เมื่อเป็น Exact หน่วยวัดคือ points หรือเมื่อเป็น Multiple หน่วยวัดคือ half-lines. ค่าเริ่มต้น: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## ดูเพิ่มเติม

* คลาส [IMathArray](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)