---
title: get_RowSpacing()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การเว้นระยะระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 ซึ่งในกรณีนั้นหน่วยวัดคือ จุด หรือ Multiple ซึ่งในกรณีนั้นหน่วยวัดคือ ครึ่งบรรทัด ค่าเริ่มต้น: 0"
type: docs
weight: 118
url: /th/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() วิธีการ

การเว้นระยะระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 เท่านั้น ซึ่งในกรณีนั้นหน่วยวัดคือ จุด หรือ Multiple ซึ่งในกรณีนั้นหน่วยวัดคือ ครึ่งบรรทัด ค่าเริ่มต้น: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## ดูเพิ่มเติม

* คลาส [MathArray](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)