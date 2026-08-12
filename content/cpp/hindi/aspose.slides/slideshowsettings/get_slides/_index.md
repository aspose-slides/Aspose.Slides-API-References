---
title: get_Slides()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्लाइड्स की रेंज
type: docs
weight: 118
url: /hi/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const विधि


[Slides](../../) रेंज

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [SlidesRange](../../slidesrange/)
* क्लास [SlideShowSettings](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)