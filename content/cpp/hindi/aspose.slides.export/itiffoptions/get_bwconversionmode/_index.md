---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API संदर्भ
description: "रंगीन छवि को काला और सफेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तब लागू होगा जब ITiffOptions::get_CompressionType() को TiffCompressionTypes::CCITT4 या TiffCompressionTypes::CCITT3 पर सेट किया गया हो। पढ़ें BlackWhiteConversionMode। डिफ़ॉल्ट BlackWhiteConversionMode::Default है।"
type: docs
weight: 183
url: /hi/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() विधि

एक रंगीन छवि को काला और सफेद छवि में परिवर्तित करने के लिए एल्गोरिदम निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [ITiffOptions::get_CompressionType()](../get_compressiontype/) को [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) पर सेट किया गया हो। पढ़ें [BlackWhiteConversionMode](../../blackwhiteconversionmode/)। डिफ़ॉल्ट [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) है।

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## टिप्पणियाँ

निम्नलिखित उदाहरण दिखाता है कि परिवर्तन एल्गोरिदम को Dithering में कैसे सेट किया जाए। 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## संबंधित देखें

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* क्लास [ITiffOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)