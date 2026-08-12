---
title: RemoveAt()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบรายการที่ดัชนีที่ระบุของคอลเลกชัน
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) วิธีการ


ลบรายการที่ดัชนีที่ระบุของคอลเลกชัน

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเริ่มจากศูนย์ของรายการที่จะลบ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## ดูเพิ่มเติม

* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)