---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API संदर्भ
description: नियत करता है कि छुपी हुई स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।
type: docs
weight: 27
url: /hi/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() विधि


यह निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## देखें

* क्लास [IGifOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)