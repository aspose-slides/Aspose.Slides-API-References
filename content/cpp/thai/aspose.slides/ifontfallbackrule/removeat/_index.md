---
title: RemoveAt()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบฟอนต์ FallBack ที่ตำแหน่งที่ระบุในรายการ.
type: docs
weight: 92
url: /th/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) เมธอด


ลบฟอนต์ FallBack ที่ตำแหน่งที่ระบุในรายการ.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่นับจากศูนย์ของฟอนต์ที่ต้องการลบ. |
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// กำลังลบ Tahoma ออกจากรายการ
newRule->RemoveAt(2);
```


## ดูเพิ่มเติม

* คลาส [IFontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)