---
title: MathSuperscriptElement()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathSuperscriptElement
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MathSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)