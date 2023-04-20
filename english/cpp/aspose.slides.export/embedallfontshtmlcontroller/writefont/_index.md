---
title: WriteFont()
second_title: Aspose.Slides for C++ API Reference
description: Writes data as base64 into HTML document itself
type: docs
weight: 105
url: /cpp/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method


Writes data as base64 into HTML document itself

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font to be serialized |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Substituted font (if font substitution occured), null otherwise |
| fontStyle | [System::String](../../../system/string/) | Font style |
| fontWeight | [System::String](../../../system/string/) | Font weight |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IFontData](../../../aspose.slides/ifontdata/)
* Class [String](../../../system/string/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)