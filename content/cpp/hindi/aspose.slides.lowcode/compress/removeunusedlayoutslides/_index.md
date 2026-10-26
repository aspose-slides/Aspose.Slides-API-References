---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन का संपीड़न करता है, अनउपयोगी लेआउट स्लाइड्स को हटाकर।
type: docs
weight: 14
url: /hi/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) विधि

अप्रयुक्त लेआउट स्लाइड्स को हटाकर [Presentation](../../../aspose.slides/presentation/) का संपीड़न करता है।

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | प्रेजेंटेशन इंस्टेंस |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [Compress](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)