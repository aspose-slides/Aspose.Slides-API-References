---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มอิลิเมนต์คณิตศาสตร์ไปยังส่วนสุดท้ายของคอลเลกชัน.
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) เมธอด

เพิ่มอิลิเมนต์คณิตศาสตร์ไปยังส่วนสุดท้ายของคอลเลกชัน.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) ที่จะถูกเพิ่มไปยังส่วนสุดท้ายของคอลเลกชัน. |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)