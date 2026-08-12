---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อาร์กิวเมนต์ Base
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() เมธอด


Base อาร์กิวเมนต์

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## ดูเพิ่มเติม

* ประเภทข้อมูล [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathRadical](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)