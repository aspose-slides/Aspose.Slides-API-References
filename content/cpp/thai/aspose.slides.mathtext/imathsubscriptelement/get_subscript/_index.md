---
title: get_Subscript()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัวห้อย
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() เมธอด

ตัวห้อย

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathSubscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)