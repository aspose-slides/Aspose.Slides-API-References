---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API संदर्भ
description: "प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान CompressionLevel::Level6 है।"
type: docs
weight: 92
url: /hi/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) विधि

प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## टिप्पणियाँ

उच्च संपीड़न स्तर छोटे फ़ाइलें उत्पन्न करते हैं, लेकिन अधिक प्रसंस्करण समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रेजेंटेशन की सामग्री पर निर्भर करता है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## संदर्भ

* Enum [CompressionLevel](../../compressionlevel/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)