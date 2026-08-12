---
title: get_DefaultRegularFont()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला Regular फ़ॉन्ट लौटाता है। पढ़ें System::String."
type: docs
weight: 27
url: /hi/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() विधि


जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला नियमित फ़ॉन्ट लौटाता है। पढ़ें [System::String](../../../system/string/)।

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## टिप्पणी


निम्नलिखित उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) के रेंडरिंग के लिए डिफ़ॉल्ट फ़ॉन्ट कैसे सेट करें। 
```cpp
// डिफ़ॉल्ट नियमित और एशियन फ़ॉन्ट को परिभाषित करने के लिए लोड विकल्पों का उपयोग करें
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// प्रस्तुति लोड करें
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// स्लाइड थंबनेल बनाएँ
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF बनाएँ
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS बनाएँ
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## देखें भी

* क्लास [String](../../../system/string/)
* क्लास [LoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)