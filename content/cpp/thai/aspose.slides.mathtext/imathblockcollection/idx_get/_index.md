---
title: idx_get()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว IMathBlock.
type: docs
weight: 92
url: /th/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) เมธอด

ดึงรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะดึง |

### ค่าที่คืน

บล็อกของข้อความคณิตศาสตร์.

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)