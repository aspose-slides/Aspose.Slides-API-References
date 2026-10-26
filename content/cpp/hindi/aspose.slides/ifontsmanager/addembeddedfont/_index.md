---
title: AddEmbeddedFont()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एम्बेडेड फ़ॉन्ट जोड़ता है।
type: docs
weight: 105
url: /hi/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) method

एम्बेडेड फ़ॉन्ट जोड़ता है।

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font data object [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## टिप्पणियाँ

फ़ॉन्ट्स को कॉपी करते समय यह ध्यान रखें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। पहले फ़ॉन्ट का लाइसेंस प्राप्त करें और यह सत्यापित करें कि उन्हें किसी अन्य मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है।

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) method

एम्बेडेड फ़ॉन्ट जोड़ता है।

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## टिप्पणियाँ

फ़ॉन्ट्स जोड़ते समय यह ध्यान रखें कि अधिकांश फ़ॉन्ट्स कॉपीराइटेड होते हैं। पहले फ़ॉन्ट का लाइसेंस प्राप्त करें और यह सत्यापित करें कि उन्हें किसी अन्य मशीन पर स्वतंत्र रूप से स्थानांतरित किया जा सकता है।

## संबंधित देखें

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)