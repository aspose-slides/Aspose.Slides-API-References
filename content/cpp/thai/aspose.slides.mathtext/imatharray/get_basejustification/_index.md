---
title: get_BaseJustification()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุการจัดแนวของอาเรย์เทียบกับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของอ็อบเจกต์อาเรย์ ค่าเริ่มต้น: Center"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() เมธอด

ระบุการจัดแนวของอาเรย์เมื่อเทียบกับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของอ็อบเจกต์อาเรย์ได้ ค่าเริ่มต้น: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## ดูเพิ่มเติม

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)