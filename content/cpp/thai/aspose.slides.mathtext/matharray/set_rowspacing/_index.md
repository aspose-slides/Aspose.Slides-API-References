---
title: set_RowSpacing()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: "ระยะห่างระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 ซึ่งในกรณีนั้นหน่วยวัดคือจุด หรือ Multiple ในกรณีที่หน่วยวัดเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0"
type: docs
weight: 131
url: /th/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) เมธอด


ระยะห่างระหว่างแถวของอาร์เรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 เท่านั้น ซึ่งในกรณีนี้หน่วยวัดคือจุด หรือ Multiple ในกรณีที่หน่วยวัดเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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