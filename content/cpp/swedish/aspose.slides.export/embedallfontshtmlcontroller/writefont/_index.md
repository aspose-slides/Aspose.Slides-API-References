---
title: WriteFont()
second_title: Aspose.Slides för C++ API-referens
description: Skriver data som base64 i HTML-dokumentet själv
type: docs
weight: 105
url: /sv/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) metod

Skriver data som base64 i HTML-dokumentet själv

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML-generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font som ska serialiseras |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Ersatt font (om fontsubstitution inträffade), null annars |
| fontStyle | [System::String](../../../system/string/) | Fontstil |
| fontWeight | [System::String](../../../system/string/) | Fontvikt |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Fontdata |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IHtmlGenerator](../../ihtmlgenerator/)
* Klass [IFontData](../../../aspose.slides/ifontdata/)
* Klass [String](../../../system/string/)
* Klass [EmbedAllFontsHtmlController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)