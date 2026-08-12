---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนดัชนีของกฎที่ระบุในคอลเลกชัน.
type: docs
weight: 118
url: /th/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) เมธอด


ส่งคืนดัชนีของกฎที่ระบุในคอลเลกชัน

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | ชื่อแบบอักษรที่ต้องการค้นหา. |

### ค่าที่ส่งคืน

ดัชนีของแบบอักษร หรือ -1 หากไม่พบแบบอักษรในรายการ
## หมายเหตุ



```cpp
// สร้างกฎที่มีรายการแบบอักษร.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// รับดัชนีของ Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IFontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)