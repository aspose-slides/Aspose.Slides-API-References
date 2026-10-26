---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนดัชนีของกฎที่ระบุในคอลเลกชัน.
type: docs
weight: 157
url: /th/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) เมธอด

ส่งคืนดัชนีของกฎที่ระบุในคอลเลกชัน.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | ชื่อฟอนต์ที่ต้องการค้นหา. |

### ค่าที่ส่งคืน

ดัชนีของฟอนต์หรือ -1 หากไม่พบฟอนต์ในรายการ.

## หมายเหตุ

```cpp
// สร้างกฎที่มีรายการฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// รับดัชนีของ Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [FontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)