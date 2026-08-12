---
title: get_Subscript()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อาร์กิวเมนต์ Subscript
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_subscript/
---
## IMathRightSubSuperscriptElement::get_Subscript() เมธอด


Subscript อาร์กิวเมนต์

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Subscript()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathRightSubSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)