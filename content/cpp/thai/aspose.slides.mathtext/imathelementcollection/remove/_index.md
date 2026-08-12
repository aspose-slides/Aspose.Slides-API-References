---
title: Remove()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ลบการปรากฏครั้งแรกของวัตถุที่ระบุออกจากคอลเลกชัน.
type: docs
weight: 92
url: /th/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) เมธอด


ลบการปรากฏครั้งแรกของวัตถุที่ระบุออกจากคอลเลกชัน.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อ็อบเจ็กต์ที่ต้องการลบออกจากคอลเลกชัน. |

### ค่าที่คืน

true หาก *item* ถูกลบออกจากคอลเลกชันสำเร็จ; มิฉะนั้น จะเป็น false. เมธอดนี้ยังคืนค่า false หากไม่พบ *item* ในคอลเลกชันต้นฉบับ.
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)