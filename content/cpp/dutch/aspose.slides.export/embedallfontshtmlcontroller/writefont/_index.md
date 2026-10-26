---
title: WriteFont()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft gegevens als base64 in het HTML-document zelf
type: docs
weight: 105
url: /nl/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) methode

Schrijft gegevens als base64 in het HTML-document zelf

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font to be serialized |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Substituted font (if font substitution occured), null otherwise |
| fontStyle | [System::String](../../../system/string/) | Font style |
| fontWeight | [System::String](../../../system/string/) | Font weight |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IFontData](../../../aspose.slides/ifontdata/)
* Klasse [String](../../../system/string/)
* Klasse [EmbedAllFontsHtmlController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)