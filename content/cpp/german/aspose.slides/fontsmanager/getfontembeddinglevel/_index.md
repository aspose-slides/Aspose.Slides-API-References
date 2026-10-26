---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt die Einbettungsstufe einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen.
type: docs
weight: 144
url: /de/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) method


Bestimmt die Einbettungsstufe einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, das die Schriftartdaten enthält. |
| fontName | [System::String](../../../system/string/) | Der Name der Schriftart. |

### Rückgabewert

Die Einbettungsstufe der angegebenen Schriftart.
## Bemerkungen




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Siehe auch

* Aufzählung [EmbeddingLevel](../../embeddinglevel/)
* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)