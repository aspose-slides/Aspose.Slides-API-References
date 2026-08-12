---
title: set_Zip64Mode()
second_title: Aspose.Slides for C++ API संदर्भ
description: "निर्दिष्ट करता है कि ZIP64 फ़ॉर्मेट Presentation दस्तावेज़ के लिए उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान Zip64Mode::IfNecessary है।"
type: docs
weight: 40
url: /hi/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) मेथड

निर्दिष्ट करता है कि ZIP64 फॉर्मेट [Presentation](../../../aspose.slides/presentation/) दस्तावेज़ के लिए उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान [Zip64Mode::IfNecessary](../../zip64mode/) है।

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* एन्युम [Zip64Mode](../../zip64mode/)
* क्लास [IPptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)