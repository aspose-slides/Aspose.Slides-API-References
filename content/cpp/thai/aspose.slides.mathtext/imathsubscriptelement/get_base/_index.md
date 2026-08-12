---
title: get_Base()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อาร์กิวเมนต์ Base
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() เมธอด

อาร์กิวเมนต์ Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
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
* คลาส [IMathSubscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)