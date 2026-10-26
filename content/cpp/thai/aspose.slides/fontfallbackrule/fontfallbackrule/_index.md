---
title: FontFallBackRule()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 66
url: /th/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | **uint32_t** | ดัชนีเริ่มต้นของช่วงยูนิโค้ด |
| endIndex | **uint32_t** | ดัชนีสิ้นสุดของช่วงยูนิโค้ด |
| fontNames | [System::String](../../../system/string/) | ชื่อหรือรายชื่อของฟอนต์ (คั่นด้วยเครื่องหมายจุลภาคม) สำหรับ FallBack |
## หมายเหตุ

```cpp
// สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยฟอนต์หนึ่งตัว.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยหลายฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | **uint32_t** | ดัชนีเริ่มต้นของช่วงยูนิโค้ด |
| endIndex | **uint32_t** | ดัชนีสิ้นสุดของช่วงยูนิโค้ด |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | ชื่อหรือรายชื่อของฟอนต์ (คั่นด้วยเครื่องหมายจุลภาคม) สำหรับ FallBack |
## หมายเหตุ

```cpp
// สร้างอินสแตนส์ใหม่ของ FantFallBackRule ด้วยฟอนต์สองตัว
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// สร้างอินสแตนส์ใหม่ของ FantFallBackRule ด้วยหลายฟอนต์.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)