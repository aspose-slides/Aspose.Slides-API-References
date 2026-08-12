---
title: ToMathArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: วางส่วนประกอบลูกในอาเรย์แนวตั้ง
type: docs
weight: 235
url: /th/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() เมธอด

วางส่วนประกอบลูกในอาเรย์แนวตั้ง

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ชนิด [IMathArray](../../imatharray/)
## หมายเหตุ


ตัวอย่าง: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathArray](../../imatharray/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)