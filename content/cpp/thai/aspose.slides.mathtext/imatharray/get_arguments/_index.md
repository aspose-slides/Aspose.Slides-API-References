---
title: get_Arguments()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ชุดของรายการในอาเรย์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() เมธอด

ชุดของรายการในอาเรย์

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElementCollection](../../imathelementcollection/)
* คลาส [IMathArray](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)