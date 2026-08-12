---
title: get_Subscript()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุอาร์กิวเมนต์ซับสคริปต์ที่, ตัวอย่างเช่น, ในกรณีของจำนวนเต็ม, กำหนดขอบล่าง
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() เมธอด

ระบุอาร์กิวเมนต์ซับสคริปต์ที่, ตัวอย่างเช่น, ในกรณีของจำนวนเต็ม, กำหนดขอบล่าง

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## หมายเหตุ

ตัวอย่าง:

```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)