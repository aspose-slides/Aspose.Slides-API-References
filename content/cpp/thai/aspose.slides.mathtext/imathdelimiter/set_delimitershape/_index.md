---
title: set_DelimiterShape()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ระบุรูปทรงของตัวแบ่งในวัตถุ delimiter. เมื่อเป็น MathDelimiterShape::Centered, ตัวแบ่งจะถูกจัดกึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา. เมื่อเป็น MathDelimiterShape::Match, ความสูงและรูปทรงของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างพอดี."
type: docs
weight: 131
url: /th/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) เมธอด

ระบุรูปทรงของตัวแบ่งในวัตถุ delimiter. เมื่อเป็น [MathDelimiterShape::Centered](../../mathdelimitershape/) ตัวแบ่งจะถูกจัดกึ่งกลางรอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์และยังคงทำให้พอดีกับความสูงทั้งหมดของเนื้อหา. เมื่อเป็น [MathDelimiterShape::Match](../../mathdelimitershape/) ความสูงและรูปทรงของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างพอดี.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## หมายเหตุ

```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## ดูเพิ่มเติม

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)