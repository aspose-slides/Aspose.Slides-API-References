---
title: WriteFont()
second_title: Aspose.Slides pro C++ API Reference
description: Zapíše data jako base64 přímo do HTML dokumentu
type: docs
weight: 105
url: /cs/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method

Zapíše data jako base64 do samotného HTML dokumentu

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generátor |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Písmo k serializaci |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Nahrazené písmo (pokud došlo k nahrazení písma), null jinak |
| fontStyle | [System::String](../../../system/string/) | Styl písma |
| fontWeight | [System::String](../../../system/string/) | Váha písma |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data písma |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IHtmlGenerator](../../ihtmlgenerator/)
* Třída [IFontData](../../../aspose.slides/ifontdata/)
* Třída [String](../../../system/string/)
* Třída [EmbedAllFontsHtmlController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)