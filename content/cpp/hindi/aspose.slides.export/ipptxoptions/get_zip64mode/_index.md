---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: "निर्देशित करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान Zip64Mode::IfNecessary है"
type: docs
weight: 27
url: /hi/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() method


निर्देशित करता है कि ZIP64 फ़ॉर्मेट [Presentation](../../../aspose.slides/presentation/) दस्तावेज़ के लिए उपयोग किया जाता है या नहीं। डिफ़ॉल्ट मान [Zip64Mode::IfNecessary](../../zip64mode/) है।

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## संबंधित देखें

* Enum [Zip64Mode](../../zip64mode/)
* क्लास [IPptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)