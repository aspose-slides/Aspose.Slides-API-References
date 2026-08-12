---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेजेंटेशन की पूरी अवधि के दौरान उपलब्ध होते हैं और अन्य प्रेजेंटेशन्स के साथ साझा नहीं किए जाते।
type: docs
weight: 222
url: /hi/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) विधि


प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेजेंटेशन के पूरे जीवनकाल में उपलब्ध होते हैं और अन्य प्रेजेंटेशन के साथ साझा नहीं होते हैं।

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## टिप्पणी


निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) के साथ उपयोग किए जाने वाले कस्टम फ़ॉन्ट्स को कैसे निर्दिष्ट किया जाए। 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// प्रेजेंटेशन के साथ काम करें
// CustomFont1, CustomFont2 के साथ-साथ assets\\fonts और global\\fonts फ़ोल्डर्स तथा उनके सबफ़ोल्डर्स से फ़ॉन्ट्स प्रेजेंटेशन के लिए उपलब्ध हैं
```

## देखें

* टाइपपरिभाषा [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontSources](../../ifontsources/)
* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)