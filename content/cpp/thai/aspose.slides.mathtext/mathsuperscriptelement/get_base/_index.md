---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อาร์กิวเมนต์ Base
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathsuperscriptelement/get_base/
---
## MathSuperscriptElement::get_Base() เมธอด


อาร์กิวเมนต์ Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)