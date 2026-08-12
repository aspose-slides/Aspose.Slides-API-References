---
title: get_Superscript()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุอาร์กิวเมนต์ supersript ที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, ตั้งค่าขอบบน
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() เมธอด


ระบุอาร์กิวเมนต์ supersript ที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, ตั้งค่าขอบบน

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)