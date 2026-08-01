---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam.
type: docs
weight: 144
url: /nl/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) methode

Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array die de lettertype-gegevens bevat. |
| fontName | [System::String](../../../system/string/) | De naam van het lettertype. |

### Retourwaarde

Het insluitingsniveau van het opgegeven lettertype.

## Opmerkingen

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Zie ook

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)