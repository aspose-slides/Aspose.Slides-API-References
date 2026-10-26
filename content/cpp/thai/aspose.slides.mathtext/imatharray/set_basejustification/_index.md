---
title: set_BaseJustification()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือกึ่งกลางของอาเรย์ได้ ค่าเริ่มต้น: Center"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) เมธอด

ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความด้านนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ได้ ค่าเริ่มต้น: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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