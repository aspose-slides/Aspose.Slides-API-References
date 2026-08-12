---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति के पूरे जीवनकाल में उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते।
type: docs
weight: 209
url: /hi/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() मेथड

प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति के पूरे जीवनकाल में उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते।

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) के साथ उपयोग किए जाने वाले कस्टम फ़ॉन्ट्स को कैसे निर्दिष्ट किया जाए।

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// प्रस्तुति के साथ काम करें
// CustomFont1, CustomFont2 के साथ-साथ assets\fonts और global\fonts फ़ोल्डरों और उनके सबफ़ोल्डरों से फ़ॉन्ट्स प्रस्तुति के लिए उपलब्ध हैं
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSources](../../ifontsources/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)