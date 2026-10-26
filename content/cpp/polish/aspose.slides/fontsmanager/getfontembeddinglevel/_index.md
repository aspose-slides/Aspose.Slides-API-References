---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa poziom osadzania czcionki na podstawie podanej tablicy bajtów i nazwy czcionki.
type: docs
weight: 144
url: /pl/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metoda

Określa poziom osadzania czcionki na podstawie podanej tablicy bajtów i nazwy czcionki.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów zawierająca dane czcionki. |
| fontName | [System::String](../../../system/string/) | Nazwa czcionki. |

### Wartość zwracana

Poziom osadzania określonej czcionki.

## Uwagi

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Zobacz także

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontsManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)