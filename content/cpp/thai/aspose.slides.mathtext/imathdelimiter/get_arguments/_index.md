---
title: get_Arguments()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่คั่นด้วยอักขระตัวคั่น
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() เมธอด


หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่คั่นด้วยอักขระตัวคั่น

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElementCollection](../../imathelementcollection/)
* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)