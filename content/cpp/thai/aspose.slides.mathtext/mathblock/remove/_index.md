---
title: Remove()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์เฉพาะจากคอลเลกชัน.
type: docs
weight: 131
url: /th/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) เมธอด


ลบการเกิดขึ้นครั้งแรกของวัตถุเฉพาะจากคอลเลกชัน

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | วัตถุที่จะลบออกจากคอลเลกชัน |

### ค่าที่คืน

true หาก *item* ถูกลบออกจากคอลเลกชันสำเร็จ; มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หาก *item* ไม่พบในคอลเลกชันต้นฉบับ

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)