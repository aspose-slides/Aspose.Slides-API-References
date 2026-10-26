---
title: get_Name()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชัน ได้แก่ sin และ cos
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() เมธอด

ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันได้แก่ sin และ cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## หมายเหตุ

ตัวอย่าง:

```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathFunction](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)