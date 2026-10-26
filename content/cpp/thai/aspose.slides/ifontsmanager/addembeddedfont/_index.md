---
title: AddEmbeddedFont()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มฟอนต์ที่ฝังไว้.
type: docs
weight: 105
url: /th/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) เมธอด

Adds the embedded font.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | วัตถุข้อมูลฟอนต์ [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | กฎฟอนต์ที่ฝัง [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## หมายเหตุ

โปรดระลึกว่าเมื่อคัดลอกฟอนต์ใด ๆ ส่วนใหญ่ฟอนต์มีลิขสิทธิ์ ควรตรวจสอบใบอนุญาตของฟอนต์ล่วงหน้าและยืนยันว่ามีการยอมให้นำไปโอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ.

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) เมธอด

Adds the embedded font

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลฟอนต์ **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | กฎฟอนต์ที่ฝัง [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## หมายเหตุ

โปรดระลึกว่าเมื่อเพิ่มฟอนต์ใด ๆ ส่วนใหญ่ฟอนต์มีลิขสิทธิ์ ควรตรวจสอบใบอนุญาตของฟอนต์ล่วงหน้าและยืนยันว่ามีการยอมให้นำไปโอนย้ายไปยังเครื่องอื่นได้อย่างอิสระ.

## ดูเพิ่มเติม

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IFontData](../../ifontdata/)
* คลาส [IFontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)