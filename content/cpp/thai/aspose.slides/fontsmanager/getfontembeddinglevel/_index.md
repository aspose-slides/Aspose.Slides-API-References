---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้มา.
type: docs
weight: 144
url: /th/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) วิธี

กำหนดระดับการฝังของแบบอักษรจากอาร์เรย์ไบต์และชื่อแบบอักษรที่ให้มา.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ไบต์ที่บรรจุข้อมูลแบบอักษร |
| fontName | [System::String](../../../system/string/) | ชื่อของแบบอักษร |

### ค่าที่ส่งกลับ

ระดับการฝังของแบบอักษรที่ระบุ.

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
* คลาส [String](../../../system/string/)
* คลาส [FontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)