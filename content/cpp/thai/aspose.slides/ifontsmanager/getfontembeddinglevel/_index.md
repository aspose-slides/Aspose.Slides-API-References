---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดระดับการฝังของฟอนต์จากอาร์เรย์ไบต์และชื่อฟอนต์ที่ให้มา.
type: docs
weight: 144
url: /th/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) เมธอด

กำหนดระดับการฝังฟอนต์จากอาร์เรย์ไบต์และชื่อฟอนต์ที่ให้มา.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array containing the font data. |
| fontName | [System::String](../../../system/string/) | The name of the font. |

### ค่าที่ส่งคืน

ระดับการฝังของฟอนต์ที่ระบุ.
## หมายเหตุ


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## ดูเพิ่มเติม

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)