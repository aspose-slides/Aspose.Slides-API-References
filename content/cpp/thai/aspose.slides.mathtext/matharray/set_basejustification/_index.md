---
title: set_BaseJustification()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุการจัดตำแหน่งของอาร์เรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาร์เรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือกึ่งกลางของอ็อบเจกต์อาร์เรย์ได้ ค่าเริ่มต้น: Center"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) เมธอด


ระบุการจัดตำแหน่งของอาร์เรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาร์เรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือกึ่งกลางของอ็อบเจกต์อาร์เรย์ได้ ค่าเริ่มต้น: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## ดูเพิ่มเติม

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* คลาส [MathArray](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)