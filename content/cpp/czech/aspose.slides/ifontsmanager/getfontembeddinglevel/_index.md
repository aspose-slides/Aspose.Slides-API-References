---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje úroveň vkládání písma z daného pole bajtů a názvu písma.
type: docs
weight: 144
url: /cs/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) metoda


Určuje úroveň vkládání písma z daného pole bajtů a názvu písma.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů obsahující data písma. |
| fontName | [System::String](../../../system/string/) | Název písma. |

### Návratová hodnota

Úroveň vkládání zadaného písma.
## Poznámky




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Získá všechny písma použité v prezentaci
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Získá pole bajtů představující pravidelný styl prvního písma v prezentaci
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Určí úroveň vkládání písma
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Viz také

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* třída [String](../../../system/string/)
* třída [IFontsManager](../)
* obor názvů [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)