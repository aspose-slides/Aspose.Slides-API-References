---
title: get_Subscript()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุอาร์กิวเมนต์ซับสคริปต์ที่ ตัวอย่างเช่น ในกรณีของจำนวนเต็ม จะกำหนดขอบเขตล่าง
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() เมธอด

ระบุอาร์กิวเมนต์ซับสคริปต์ที่ ตัวอย่างเช่น ในกรณีของจำนวนเต็ม จะตั้งค่าขีดจำกัดล่าง

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## ดูเพิ่มเติม

* ประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)