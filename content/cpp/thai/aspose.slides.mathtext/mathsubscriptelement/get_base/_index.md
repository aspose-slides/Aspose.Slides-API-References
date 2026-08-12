---
title: get_Base()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: อาร์กิวเมนต์ Base
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathsubscriptelement/get_base/
---
## MathSubscriptElement::get_Base() เมธอด


อาร์กิวเมนต์ Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Base() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathSubscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)