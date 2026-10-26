---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดดัชนีของส่วนประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน.
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) เมธอด

กำหนดดัชนีของส่วนประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบที่ต้องการค้นหาในคอลเลกชัน. |

### ค่าที่ส่งกลับ

ดัชนีของ *item* หากพบในคอลเลกชัน; หากไม่พบจะเป็น -1.
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)