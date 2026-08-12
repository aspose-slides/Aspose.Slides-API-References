---
title: get_Superscript()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวยก
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() เมธอด

Superscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathLeftSubSuperscriptElement](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)