---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: อาร์กิวเมนต์ Base
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() method


Base อาร์กิวเมนต์

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathPhantom](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)