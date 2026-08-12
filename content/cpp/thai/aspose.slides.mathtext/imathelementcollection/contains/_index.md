---
title: Contains()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) เมธอด

กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อ็อบเจ็กต์ที่ต้องการค้นหาในคอลเลกชัน |

### ค่าที่ส่งคืน

true หาก *item* พบในคอลเลกชัน; มิฉะนั้น false.
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)