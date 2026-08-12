---
title: Remove()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบการปรากฏครั้งแรกของฟอนต์ FallBack ที่ระบุจากรายการ.
type: docs
weight: 118
url: /th/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) เมธอด


ลบการปรากฏครั้งแรกของฟอนต์ FallBack ที่ระบุจากรายการ.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | ชื่อฟอนต์ที่จะลบออกจากรายการ. |
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// ลบ Tahoma ออกจากรายการ.
newRule->Remove(u"Tahoma");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [FontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)