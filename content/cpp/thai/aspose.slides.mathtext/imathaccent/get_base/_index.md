---
title: get_Base()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อาร์กิวเมนต์ที่ถูกใช้กับสำเนียง
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() เมธอด

อาร์กิวเมนต์ที่ถูกใช้กับสำเนียง

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## ดูเพิ่มเติม

* ชนิดกำหนดใหม่ [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathAccent](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)