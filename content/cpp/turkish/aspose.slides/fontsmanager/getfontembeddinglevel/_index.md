---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bayt dizisi ve yazı tipi adından bir yazı tipinin gömme seviyesini belirler.
type: docs
weight: 144
url: /tr/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metot


Belirtilen bayt dizisinden ve yazı tipi adından bir yazı tipinin gömme seviyesini belirler.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Yazı tipi verilerini içeren bayt dizisi. |
| fontName | [System::String](../../../system/string/) | Yazı tipinin adı. |

### Dönüş Değeri

Belirtilen yazı tipinin gömme seviyesi.
## Açıklamalar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Ayrıca Bakınız

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FontsManager](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)