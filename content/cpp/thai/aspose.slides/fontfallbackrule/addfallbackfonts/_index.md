---
title: AddFallBackFonts()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มฟอนต์ใหม่(s) ไปยังรายการฟอนต์ FallBack.
type: docs
weight: 79
url: /th/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) เมธอด


เพิ่มฟอนต์ใหม่(s) ไปยังรายการฟอนต์ FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | ชื่อหรือชื่อของฟอนต์ (คั่นด้วยเครื่องหมายจุลภาค) สำหรับ FallBack |
## หมายเหตุ



```cpp
// สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//เพิ่มฟอนต์ที่สองเข้ากฎ
newRule->AddFallBackFonts(u"MS Gothic");
//เพิ่มฟอนต์ที่สามและสี่เข้ากฎ
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) เมธอด


เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | ชื่อหรือชื่อของฟอนต์ (คั่นด้วยเครื่องหมายจุลภาค) สำหรับ FallBack |
## หมายเหตุ



```cpp
//สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//เพิ่มฟอนต์อีกสามตัวเข้ากฎ
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [FontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)