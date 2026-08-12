---
title: set_BwConversionMode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म को निर्दिष्ट करता है। यह विकल्प केवल तब लागू होगा जब ITiffOptions::get_CompressionType() को TiffCompressionTypes::CCITT4 या TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode पर सेट किया गया हो। डिफ़ॉल्ट BlackWhiteConversionMode::Default है।"
type: docs
weight: 209
url: /hi/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) विधि

एक रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म को निर्दिष्ट करता है। यह विकल्प केवल तब लागू होगा जब [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) को [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) पर सेट किया गया हो। डिफ़ॉल्ट [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) है।

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## टिप्पणी

निम्नलिखित उदाहरण दिखाता है कि कैसे परिवर्तन एल्गोरिद्म को Dithering पर सेट किया जाए। 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## संबंधित देखें

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)