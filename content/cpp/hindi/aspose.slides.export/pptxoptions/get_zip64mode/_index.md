---
title: get_Zip64Mode()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया गया है या नहीं। डिफ़ॉल्ट मान Zip64Mode::IfNecessary है।"
type: docs
weight: 27
url: /hi/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() विधि

निर्दिष्ट करता है कि ZIP64 फ़ॉर्मेट [Presentation](../../../aspose.slides/presentation/) दस्तावेज़ के लिए उपयोग किया गया है या नहीं। डिफ़ॉल्ट मान [Zip64Mode::IfNecessary](../../zip64mode/) है।

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* Enum [Zip64Mode](../../zip64mode/)
* क्लास [PptxOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)