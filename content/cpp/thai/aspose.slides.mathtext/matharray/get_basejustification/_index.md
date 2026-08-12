---
title: get_BaseJustification()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดการจัดแนวของอาร์เรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาร์เรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาร์เรย์ ค่าเริ่มต้น: Center"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() เมธอด

กำหนดการจัดแนวของอาร์เรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาร์เรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาร์เรย์ได้ ค่าเริ่มต้น: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## ดูเพิ่มเติม

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)