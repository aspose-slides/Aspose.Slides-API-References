---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट का एम्बेडिंग स्तर निर्धारित करता है।
type: docs
weight: 144
url: /hi/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) विधि

दिए गए बाइट एरे और फ़ॉन्ट नाम से फ़ॉन्ट का एम्बेडिंग स्तर निर्धारित करता है।

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | फ़ॉन्ट डेटा वाले बाइट एरे। |
| fontName | [System::String](../../../system/string/) | फ़ॉन्ट का नाम। |

### वापसी मान

निर्दिष्ट फ़ॉन्ट का एम्बेडिंग स्तर।

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## देखें

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [IFontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)