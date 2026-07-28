---
title: WriteFont()
second_title: Aspose.Slides C++ API hivatkozás
description: Az adatokat base64 formátumban a HTML dokumentumba írja.
type: docs
weight: 105
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) metódus

Az adatokat base64 formátumban írja a HTML dokumentumba

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generátor |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Serializálandó betűtípus |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Helyettesített betűtípus (ha betűkészlet-helyettesítés történt), egyébként null |
| fontStyle | [System::String](../../../system/string/) | Betűstílus |
| fontWeight | [System::String](../../../system/string/) | Betűvastagság |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Betűtípus adat |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IHtmlGenerator](../../ihtmlgenerator/)
* Osztály [IFontData](../../../aspose.slides/ifontdata/)
* Osztály [String](../../../system/string/)
* Osztály [EmbedAllFontsHtmlController](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)