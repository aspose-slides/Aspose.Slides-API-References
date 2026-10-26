---
title: set_Zip64Mode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "निर्दिष्ट करता है कि ZIP64 फ़ॉर्मेट Presentation दस्तावेज़ के लिए उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान Zip64Mode::IfNecessary है।"
type: docs
weight: 40
url: /hi/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) विधि


निर्दिष्ट करता है कि ZIP64 फ़ॉर्मेट [Presentation](../../../aspose.slides/presentation/) दस्तावेज़ के लिए उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान [Zip64Mode::IfNecessary](../../zip64mode/) है।

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)