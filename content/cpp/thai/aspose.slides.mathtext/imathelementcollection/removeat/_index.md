---
title: RemoveAt()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุออกจากคอลเลกชัน.
type: docs
weight: 105
url: /th/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) เมธอด


ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุออกจากคอลเลกชัน.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบที่ต้องการลบ. |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## ดูเพิ่มเติม

* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)