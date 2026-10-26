---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी। डिफ़ॉल्ट मान false है।
type: docs
weight: 40
url: /hi/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) मेथड


निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी। डिफ़ॉल्ट मान false है।

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## संबंधित देखें

* क्लास [GifOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)