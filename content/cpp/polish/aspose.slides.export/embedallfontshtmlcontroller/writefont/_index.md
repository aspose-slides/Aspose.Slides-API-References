---
title: WriteFont()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zapisuje dane jako base64 w samym dokumencie HTML
type: docs
weight: 105
url: /pl/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) metoda

Zapisuje dane jako base64 bezpośrednio w dokumencie HTML

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | generator HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Czcionka do serializacji |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Zastąpiona czcionka (jeśli wystąpiła zamiana czcionki), null w przeciwnym razie |
| fontStyle | [System::String](../../../system/string/) | Styl czcionki |
| fontWeight | [System::String](../../../system/string/) | Waga czcionki |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane czcionki |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [IHtmlGenerator](../../ihtmlgenerator/)
* Klasa [IFontData](../../../aspose.slides/ifontdata/)
* Klasa [String](../../../system/string/)
* Klasa [EmbedAllFontsHtmlController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)