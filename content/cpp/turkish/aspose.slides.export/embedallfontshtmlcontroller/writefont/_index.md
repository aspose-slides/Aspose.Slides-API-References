---
title: WriteFont()
second_title: Aspose.Slides için C++ API Referansı
description: Verileri base64 olarak HTML belgesine yazar
type: docs
weight: 105
url: /tr/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) metod

Verileri base64 olarak HTML belgesine yazar

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML üreteci |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Serileştirilecek yazı tipi |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Yerine geçen yazı tipi (yazı tipi ikamesi gerçekleştiyse), aksi takdirde null |
| fontStyle | [System::String](../../../system/string/) | Yazı tipi stili |
| fontWeight | [System::String](../../../system/string/) | Yazı tipi kalınlığı |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Yazı tipi verisi |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IHtmlGenerator](../../ihtmlgenerator/)
* Sınıf [IFontData](../../../aspose.slides/ifontdata/)
* Sınıf [String](../../../system/string/)
* Sınıf [EmbedAllFontsHtmlController](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)