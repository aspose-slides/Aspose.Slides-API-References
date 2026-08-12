---
title: get_Base()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อาร์กิวเมนต์ Base
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_base/
---
## MathRightSubSuperscriptElement::get_Base() เมธอด


อาร์กิวเมนต์ Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathRightSubSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)