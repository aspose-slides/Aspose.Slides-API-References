---
title: get_RowSpacing()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ระยะห่างระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 ซึ่งในกรณีนั้นหน่วยวัดคือจุด หรือ Multiple ซึ่งในกรณีนั้นหน่วยวัดคือครึ่งบรรทัด ค่าเริ่มต้น: 0"
type: docs
weight: 118
url: /th/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() เมธอด

ระยะห่างระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 ซึ่งในกรณีนั้นหน่วยวัดคือจุด หรือ Multiple ซึ่งในกรณีนั้นหน่วยวัดคือครึ่งบรรทัด ค่าเริ่มต้น: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
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