---
title: Compress
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन को संपीड़ित करने के उद्देश्य से विधियों के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 14
url: /hi/aspose.slides.lowcode/compress/
---
## Compress क्लास

[Presentation](../../aspose.slides/presentation/) को संपीड़ित करने के उद्देश्य से विधियों के समूह का प्रतिनिधित्व करता है।

```cpp
class Compress
```

## विधियां

| विधि | विवरण |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/) का संपीड़न एंबेडेड फ़ॉन्ट्स से अप्रयुक्त अक्षरों को हटाकर करता है। |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/) का संपीड़न अप्रयुक्त लेआउट स्लाइड्स को हटाकर करता है। |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/) का संपीड़न अप्रयुक्त मास्टर स्लाइड्स को हटाकर करता है। |
## टिप्पणियां

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* नेमस्पेस [Aspose::Slides::LowCode](../)
* लाइब्रेरी [Aspose.Slides](../../)