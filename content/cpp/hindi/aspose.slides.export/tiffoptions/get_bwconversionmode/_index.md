---
title: get_BwConversionMode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "रंगीन छवि को काली और सफेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब ITiffOptions::get_CompressionType() को TiffCompressionTypes::CCITT4 या TiffCompressionTypes::CCITT3 पर सेट किया गया हो। Read BlackWhiteConversionMode. डिफ़ॉल्ट BlackWhiteConversionMode::Default है।"
type: docs
weight: 196
url: /hi/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() विधि


रंगीन छवि को काली और सफेद छवि में परिवर्तित करने के लिए एल्गोरिदम निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) को [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) पर सेट किया गया हो। [BlackWhiteConversionMode](../../blackwhiteconversionmode/) पढ़ें। डिफ़ॉल्ट [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) है।

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## टिप्पणी


निम्न उदाहरण दिखाता है कि रूपांतरण एल्गोरिदम को डिथरिंग पर कैसे सेट किया जाए। 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## संबंधित देखें

* एन्यूम [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* क्लास [TiffOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)