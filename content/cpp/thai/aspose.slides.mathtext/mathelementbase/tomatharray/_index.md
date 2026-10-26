---
title: ToMathArray()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ใส่ลงในอาเรย์แนวตั้ง
type: docs
weight: 170
url: /th/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() เมธอด


ใส่ลงในอาเรย์แนวตั้ง

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathArray](../../imatharray/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathArray](../../imatharray/)
* คลาส [MathElementBase](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)