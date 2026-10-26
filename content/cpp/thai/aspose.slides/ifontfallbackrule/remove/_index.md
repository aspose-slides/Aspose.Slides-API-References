---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบการปรากฏตัวครั้งแรกของฟอนต์ FallBack เฉพาะจากรายการ.
type: docs
weight: 79
url: /th/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) เมธอด


ลบการปรากฏตัวครั้งแรกของฟอนต์ FallBack เฉพาะจากรายการ.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | ชื่อฟอนต์ที่จะลบจากรายการ |
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการฟอนต์
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// ลบ Tahoma จากรายการ
newRule->Remove(u"Tahoma");
```


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IFontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)