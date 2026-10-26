---
title: ToMathArray()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ใส่ในอาเรย์แนวตั้ง
type: docs
weight: 183
url: /th/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() เมธอด


ใส่ในอาเรย์แนวตั้ง

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
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
* คลาส [IMathElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)