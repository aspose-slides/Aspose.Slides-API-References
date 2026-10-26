---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับอิลเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว IMathElement.
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) เมธอด


รับอิลเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการรับ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathElementCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)