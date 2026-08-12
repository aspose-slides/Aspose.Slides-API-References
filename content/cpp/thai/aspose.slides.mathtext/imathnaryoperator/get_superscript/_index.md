---
title: get_Superscript()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุอาร์กิวเมนต์ซูเปอร์สคริปต์ที่, ตัวอย่างเช่น, ในกรณีของการอินทิกรัล, ตั้งค่าขอบบน
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() เมธอด


ระบุอาร์กิวเมนต์ซูเปอร์สคริปต์ที่, ตัวอย่างเช่น, ในกรณีของการอินทิกรัล, ตั้งค่าขอบบน

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
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
* คลาส [IMathNaryOperator](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)