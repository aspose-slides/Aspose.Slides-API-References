---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API संदर्भ
description: "प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान CompressionLevel::Level6 है।"
type: docs
weight: 79
url: /hi/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() विधि


प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किया जाने वाला संपीड़न स्तर निर्दिष्ट करता है। डिफ़ॉल्ट मान [CompressionLevel::Level6](../../compressionlevel/) है।

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## टिप्पणियाँ


ऊँचे संपीड़न स्तर छोटे फाइलें बनाते हैं लेकिन अधिक प्रसंस्करण समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रेजेंटेशन की सामग्री पर निर्भर करता है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* Enum [CompressionLevel](../../compressionlevel/)
* क्लास [IPptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)