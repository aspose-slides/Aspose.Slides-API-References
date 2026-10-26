---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer inbäddningsnivån för ett teckensnitt från den givna bytearrayen och teckensnittsnamnet.
type: docs
weight: 144
url: /sv/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metod


Bestämmer inbäddningsnivån för ett teckensnitt från den givna bytearrayen och teckensnittsnamnet.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen som innehåller teckensnittsdata. |
| fontName | [System::String](../../../system/string/) | Namnet på teckensnittet. |

### Returvärde

Inbäddningsnivån för det angivna teckensnittet.
## Anmärkningar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Se även

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)