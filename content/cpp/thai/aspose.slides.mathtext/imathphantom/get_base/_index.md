---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อาร์กิวเมนต์ฐาน
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() เมธอด


อาร์กิวเมนต์ฐาน

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## หมายเหตุ


ตัวอย่าง:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathPhantom](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)