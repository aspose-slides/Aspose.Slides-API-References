---
title: Add()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่ม IMathBlock ไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) เมธอด


เพิ่ม [IMathBlock](../../imathblock/) ไปยังส่วนท้ายของคอลเลกชัน.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| รายการ | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | บล็อกทางคณิตศาสตร์ที่ถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)