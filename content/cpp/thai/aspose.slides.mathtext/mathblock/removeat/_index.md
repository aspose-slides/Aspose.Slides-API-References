---
title: RemoveAt()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน
type: docs
weight: 170
url: /th/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) เมธอด

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีแบบศูนย์ฐานขององค์ประกอบที่ต้องการลบ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## ดูเพิ่มเติม

* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)