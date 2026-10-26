---
title: AddEmbeddedFont()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till det inbäddade teckensnittet.
type: docs
weight: 105
url: /sv/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) metod

Lägger till det inbäddade teckensnittet.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Fontdataobjekt [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Inbäddad teckensnittregel [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## Anmärkningar

Kom ihåg att när du kopierar teckensnitt är de flesta teckensnitt upphovsrättsskyddade. Lokalisera först licensen för ett teckensnitt i förväg och verifiera att de kan överföras fritt till en annan maskin.

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) metod

Lägger till det inbäddade teckensnittet

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Fontdata **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Inbäddad teckensnittregel [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## Anmärkningar

Kom ihåg att när du lägger till teckensnitt är de flesta teckensnitt upphovsrättsskyddade. Lokalisera först licensen för ett teckensnitt i förväg och verifiera att de kan överföras fritt till en annan maskin.

## Se även

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)