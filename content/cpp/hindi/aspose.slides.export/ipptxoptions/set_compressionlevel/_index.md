---
title: set_CompressionLevel()
second_title: "Aspose.Slides C++ के लिए API रेफ़रेंस"
description: "प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान CompressionLevel::Level6 है।"
type: docs
weight: 92
url: /hi/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) मेथड

प्रेजेंटेशन दस्तावेज़ को सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel::Level6](../../compressionlevel/)।

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## टिप्पणी

उच्च संपीड़न स्तर छोटे फ़ाइलें उत्पन्न करते हैं लेकिन अधिक प्रसंस्करण समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रेजेंटेशन की सामग्री पर निर्भर करता है।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* एनुम [CompressionLevel](../../compressionlevel/)
* क्लास [IPptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)