---
title: get_Limit()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อาร์กิวเมนต์ Limit
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() เมธอด


อาร์กิวเมนต์ Limit

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
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
* คลาส [IMathLimit](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)