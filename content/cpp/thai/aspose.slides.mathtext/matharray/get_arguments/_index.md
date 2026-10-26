---
title: get_Arguments()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ชุดของรายการในอาร์เรย์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() เมธอด


ชุดของรายการในอาร์เรย์

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## ดูเพิ่มเติม

* นิยามประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElementCollection](../../imathelementcollection/)
* คลาส [MathArray](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)