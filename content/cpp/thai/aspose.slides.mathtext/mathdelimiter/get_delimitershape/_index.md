---
title: get_DelimiterShape()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "ระบุรูปทรงของตัวคั่นในอ็อบเจ็กต์ตัวคั่น เมื่อเป็น MathDelimiterShape::Centered ตัวคั่นจะถูกจัดให้อยู่กึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา เมื่อเป็น MathDelimiterShape::Match ความสูงและรูปทรงของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ"
type: docs
weight: 118
url: /th/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() วิธีการ

กำหนดรูปทรงของตัวคั่นในอ็อบเจ็กต์ตัวคั่น. เมื่อเป็น [MathDelimiterShape::Centered](../../mathdelimitershape/), ตัวคั่นจะถูกจัดกึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา. เมื่อเป็น [MathDelimiterShape::Match](../../mathdelimitershape/), ความสูงและรูปทรงของมันจะถูกเปลี่ยนแปลงให้ตรงกับเนื้อหาอย่างแม่นยำ.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## ดูเพิ่มเติม

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)