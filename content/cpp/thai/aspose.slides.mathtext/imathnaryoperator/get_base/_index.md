---
title: get_Base()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: อาร์กิวเมนต์ Base
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathnaryoperator/get_base/
---
## IMathNaryOperator::get_Base() เมธอด


Base อาร์กิวเมนต์

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Base()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)