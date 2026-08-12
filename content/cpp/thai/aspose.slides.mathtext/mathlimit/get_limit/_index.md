---
title: get_Limit()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อาร์กิวเมนต์ Limit
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() เมธอด


อาร์กิวเมนต์ Limit

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathLimit](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)