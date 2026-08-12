---
title: AddFallBackFonts()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มฟอนต์ใหม่ลงในรายการฟอนต์ FallBack
type: docs
weight: 40
url: /th/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) method

เพิ่มฟอนต์ใหม่ลงในรายการฟอนต์ FallBack

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## หมายเหตุ

```cpp
//สร้างอินสแตนซ์ใหม่ของ FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//เพิ่มฟอนต์ที่สองลงในกฎ
newRule->AddFallBackFonts(u"MS Gothic");
//เพิ่มฟอนต์ที่สามและสี่ลงในกฎ
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) method

เพิ่มฟอนต์ใหม่ลงในรายการฟอนต์ FallBack

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## หมายเหตุ

```cpp
//สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//เพิ่มฟอนต์อีกสามฟอนต์ลงในกฎ
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [IFontFallBackRule](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)