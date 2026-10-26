---
title: get_Base()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อาร์กิวเมนต์ที่สำเนียงถูกนำไปใช้
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() เมธอด


อาร์กิวเมนต์ที่สำเนียงถูกนำไปใช้

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathAccent](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)