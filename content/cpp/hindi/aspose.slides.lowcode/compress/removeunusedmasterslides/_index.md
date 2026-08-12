---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: अप्रयुक्त मास्टर स्लाइड्स को हटाकर प्रेजेंटेशन का संपीड़न करता है।
type: docs
weight: 1
url: /hi/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) विधि

[Presentation](../../../aspose.slides/presentation/) का संपीड़न करता है, अप्रयुक्त मास्टर स्लाइड्स को हटाकर।

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | प्रेजेंटेशन का उदाहरण |

## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [Compress](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)