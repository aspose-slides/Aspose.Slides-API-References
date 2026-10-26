---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza egy betűkészlet beágyazási szintjét a megadott bájt tömbből és a betűkészlet nevéből.
type: docs
weight: 144
url: /hu/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metódus

Meghatározza a betűkészlet beágyazási szintjét a megadott bájt tömbből és a betűkészlet neve alapján.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A betűkészlet adatát tartalmazó bájt tömb. |
| fontName | [System::String](../../../system/string/) | A betűkészlet neve. |

### Visszatérési érték

A megadott betűkészlet beágyazási szintje.

## Megjegyzések

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Kapcsolódó elemek

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [IFontsManager](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)