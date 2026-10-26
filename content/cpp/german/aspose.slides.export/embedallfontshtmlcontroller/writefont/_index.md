---
title: WriteFont()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt Daten als Base64 in das HTML-Dokument selbst
type: docs
weight: 105
url: /de/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) Methode


Schreibt Daten als Base64 in das HTML-Dokument selbst

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML-Generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Schriftart zum Serialisieren |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Ersetzte Schriftart (wenn Schriftart-Ersetzung aufgetreten ist), andernfalls null |
| fontStyle | [System::String](../../../system/string/) | Schriftstil |
| fontWeight | [System::String](../../../system/string/) | Schriftgewicht |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Schriftdaten |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IHtmlGenerator](../../ihtmlgenerator/)
* Klasse [IFontData](../../../aspose.slides/ifontdata/)
* Klasse [String](../../../system/string/)
* Klasse [EmbedAllFontsHtmlController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)