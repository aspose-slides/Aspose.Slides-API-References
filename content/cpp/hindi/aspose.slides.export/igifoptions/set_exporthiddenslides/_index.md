---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।
type: docs
weight: 40
url: /hi/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) विधि

निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है।

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## टिप्पणियां



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## साथ देखें

* क्लास [IGifOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)