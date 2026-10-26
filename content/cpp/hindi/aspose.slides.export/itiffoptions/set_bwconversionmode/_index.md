---
title: set_BwConversionMode()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब ITiffOptions::get_CompressionType() को TiffCompressionTypes::CCITT4 या TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode पर सेट किया गया हो। डिफॉल्ट BlackWhiteConversionMode::Default है।"
type: docs
weight: 196
url: /hi/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) मेथड

रंगीन छवि को काली और सफेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [ITiffOptions::get_CompressionType()](../get_compressiontype/) को [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) पर सेट किया गया हो। डिफॉल्ट [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) है।

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## टिप्पणियां

निम्नलिखित उदाहरण दर्शाता है कि कैसे परिवर्तन एल्गोरिद्म को Dithering पर सेट किया जाए।

```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## देखें

* एनम [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* क्लास [ITiffOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)