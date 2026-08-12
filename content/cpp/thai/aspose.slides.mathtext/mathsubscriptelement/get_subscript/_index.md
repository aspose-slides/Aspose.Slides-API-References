---
title: get_Subscript()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตัวห้อย
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() เมธอด

ตัวห้อย

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
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

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathSubscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)