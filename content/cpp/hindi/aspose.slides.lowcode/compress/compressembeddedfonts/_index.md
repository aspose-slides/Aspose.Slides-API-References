---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides for C++ API संदर्भ
description: एंबेडेड फ़ॉन्ट्स से अनुपयोगी अक्षरों को हटाकर प्रेज़ेंटेशन का संपीड़न करता है।
type: docs
weight: 27
url: /hi/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) विधि

[Presentation](../../../aspose.slides/presentation/) का संपीड़न एम्बेडेड फ़ॉन्ट्स से अनुपयोगी अक्षरों को हटाकर करता है।

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | प्रेज़ेंटेशन उदाहरण |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [Compress](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)