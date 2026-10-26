---
title: Contains()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าชุดข้อมูลมีค่าที่ระบุหรือไม่.
type: docs
weight: 66
url: /th/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) เมธอด


กำหนดว่าชุดข้อมูลมีค่าที่ระบุหรือไม่.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | วัตถุที่ต้องการค้นหาในชุดข้อมูล. |

### ค่าที่คืนกลับ

true หาก *item* พบในชุดข้อมูล; มิฉะนั้น false.
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathBlockCollection](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)