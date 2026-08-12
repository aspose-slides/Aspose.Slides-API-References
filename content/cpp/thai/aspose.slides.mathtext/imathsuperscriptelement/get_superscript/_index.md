---
title: get_Superscript()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตัวยก
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathsuperscriptelement/get_superscript/
---
## IMathSuperscriptElement::get_Superscript() เมธอด


ตัวห้อย

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Superscript()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)