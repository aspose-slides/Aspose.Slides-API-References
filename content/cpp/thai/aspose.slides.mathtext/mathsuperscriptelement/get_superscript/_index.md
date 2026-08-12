---
title: get_Superscript()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตัวยก
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() เมธอด


ตัวยก

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
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

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)