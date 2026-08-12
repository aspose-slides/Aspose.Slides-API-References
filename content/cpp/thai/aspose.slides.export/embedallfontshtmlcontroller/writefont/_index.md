---
title: WriteFont()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เขียนข้อมูลเป็น base64 ลงในเอกสาร HTML เอง
type: docs
weight: 105
url: /th/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method


เขียนข้อมูลเป็น base64 ลงในเอกสาร HTML เอง

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font to be serialized |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Substituted font (if font substitution occured), null otherwise |
| fontStyle | [System::String](../../../system/string/) | Font style |
| fontWeight | [System::String](../../../system/string/) | Font weight |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IHtmlGenerator](../../ihtmlgenerator/)
* คลาส [IFontData](../../../aspose.slides/ifontdata/)
* คลาส [String](../../../system/string/)
* คลาส [EmbedAllFontsHtmlController](../)
* เนมสเปส [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)