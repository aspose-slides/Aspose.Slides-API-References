---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อาร์กิวเมนต์ฟังก์ชัน
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() เมธอด


อาร์กิวเมนต์ฟังก์ชัน

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathFunction](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)