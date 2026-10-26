---
title: RemoveAt()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบฟอนต์ FallBack ที่ตำแหน่งที่ระบุของรายการ.
type: docs
weight: 131
url: /th/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) เมธอด

ลบฟอนต์ FallBack ที่ตำแหน่งที่ระบุของรายการ.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของฟอนต์ที่จะลบ. |

## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//ลบ Tahoma ออกจากรายการ.
newRule->RemoveAt(2);
```

## ดูเพิ่มเติม

* คลาส [FontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)