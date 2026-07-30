---
title: WriteFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive i dati come base64 nel documento HTML stesso
type: docs
weight: 105
url: /it/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method

Scrive i dati come base64 nel documento HTML stesso

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | generatore HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | carattere da serializzare |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | carattere sostituito (se è avvenuta la sostituzione del carattere), null altrimenti |
| fontStyle | [System::String](../../../system/string/) | stile del carattere |
| fontWeight | [System::String](../../../system/string/) | peso del carattere |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | dati del carattere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IFontData](../../../aspose.slides/ifontdata/)
* Classe [String](../../../system/string/)
* Classe [EmbedAllFontsHtmlController](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)