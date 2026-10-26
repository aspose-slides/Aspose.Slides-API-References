---
title: get_CompressionLevel()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "प्रस्तुति दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान CompressionLevel::Level6 है।"
type: docs
weight: 79
url: /hi/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() विधि

प्रस्तुति दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान [CompressionLevel::Level6](../../compressionlevel/) है।

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## टिप्पणियाँ

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रसंस्करण समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रस्तुति की सामग्री पर निर्भर करता है।

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें भी

* Enum [CompressionLevel](../../compressionlevel/)
* क्लास [PptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)