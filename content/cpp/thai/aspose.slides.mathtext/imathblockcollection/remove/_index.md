---
title: Remove()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ลบการเกิดขึ้นครั้งแรกของออบเจ็กต์เฉพาะจากคอลเลกชัน/>
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) เมธอด


ลบการเกิดขึ้นครั้งแรกของออบเจ็กต์เฉพาะจากคอลเลกชัน/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | ออบเจ็กต์ที่จะลบออกจากคอลเลกชัน. |

### ค่าที่ส่งกลับ

true หาก *item*  ถูกลบออกจากคอลเลกชันสำเร็จ; มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หาก *item*  ไม่พบในคอลเลกชันเดิม/>.

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)