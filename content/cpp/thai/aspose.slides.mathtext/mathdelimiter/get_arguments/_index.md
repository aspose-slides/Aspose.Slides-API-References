---
title: get_Arguments()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่คั่นด้วยอักขระตัวคั่น
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() เมธอด

หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่คั่นด้วยอักขระตัวคั่น

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElementCollection](../../imathelementcollection/)
* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)