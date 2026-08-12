---
title: get_Subscript()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตัวห้อย
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() เมธอด


Subscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathLeftSubSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)