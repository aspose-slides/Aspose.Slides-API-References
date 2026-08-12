---
title: get_Base()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อาร์กิวเมนต์ Base
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() เมธอด


อาร์กิวเมนต์ Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // รากลูกบาศก์
auto baseElem = radical->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathRadical](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)