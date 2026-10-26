---
title: set_DelimiterShape()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ระบุรูปร่างของตัวแบ่งในอ็อบเจกต์ delimiter เมื่อเป็น MathDelimiterShape::Centered ตัวแบ่งจะถูกจัดให้อยู่ตรงกลางแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหาของมัน เมื่อเป็น MathDelimiterShape::Match ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างพอดี"
type: docs
weight: 131
url: /th/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) เมธอด

ระบุรูปร่างของตัวแบ่งในอ็อบเจกต์ delimiter เมื่อเป็น [MathDelimiterShape::Centered](../../mathdelimitershape/) ตัวแบ่งจะถูกจัดให้อยู่ตรงกลางแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหาของมัน เมื่อเป็น [MathDelimiterShape::Match](../../mathdelimitershape/) ความสูงและรูปร่างของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างพอดี

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
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