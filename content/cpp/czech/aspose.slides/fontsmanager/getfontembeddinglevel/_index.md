---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje úroveň vkládání fontu z daného pole bajtů a názvu fontu.
type: docs
weight: 144
url: /cs/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metoda


Určuje úroveň vkládání fontu z daného pole bajtů a názvu fontu.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující data fontu. |
| fontName | [System::String](../../../system/string/) | Název fontu. |

### Návratová hodnota

Úroveň vkládání specifikovaného fontu.
## Poznámky




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Získat všechny fonty použité v prezentaci
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Získat pole bajtů představující běžný styl prvního fontu v prezentaci
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Určit úroveň vkládání fontu
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Viz také

* Výčet [EmbeddingLevel](../../embeddinglevel/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [FontsManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)