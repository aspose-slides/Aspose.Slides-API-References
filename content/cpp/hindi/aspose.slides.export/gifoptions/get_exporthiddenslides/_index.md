---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।
type: docs
weight: 27
url: /hi/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() मेथड

निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## टिप्पणियाँ

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