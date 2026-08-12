---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่.
type: docs
weight: 105
url: /th/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) method

กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | วัตถุที่ต้องการค้นหาในคอลเลกชัน |

### ค่าที่คืนค่า

true หากพบ *item* ในคอลเลกชัน; มิฉะนั้น false
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)