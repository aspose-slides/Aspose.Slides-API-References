---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: "यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला नियमित फ़ॉन्ट सेट करता है। System::String लिखें।"
type: docs
weight: 40
url: /hi/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) मेथड


जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को सेट करता है। Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## टिप्पणियाँ


निम्न उदाहरण दर्शाता है कि PowerPoint [Presentation](../../presentation/) के रेंडरिंग के लिए डिफ़ॉल्ट फ़ॉन्ट कैसे सेट करें। 
```cpp
// डिफ़ॉल्ट नियमित और एशियन फ़ॉन्ट्स को परिभाषित करने के लिए लोड विकल्पों का उपयोग करें
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// प्रेजेंटेशन लोड करें
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// स्लाइड थंबनेल जनरेट करें
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF जनरेट करें
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS जनरेट करें
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)