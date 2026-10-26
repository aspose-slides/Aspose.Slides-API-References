---
title: get_DelimiterShape()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "กำหนดรูปร่างของเครื่องหมายแบ่งในออบเจ็กต์ delimiter. เมื่อเป็น MathDelimiterShape::Centered, เครื่องหมายแบ่งจะถูกจัดกึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหาของมัน. เมื่อเป็น MathDelimiterShape::Match, ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ."
type: docs
weight: 118
url: /th/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() เมธอด


ระบรูปร่างของเครื่องหมายแบ่งในออบเจ็กต์ delimiter. เมื่อเป็น [MathDelimiterShape::Centered](../../mathdelimitershape/) เครื่องหมายแบ่งจะถูกจัดกึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหาของมัน. เมื่อเป็น [MathDelimiterShape::Match](../../mathdelimitershape/) ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## ดูเพิ่มเติม

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)