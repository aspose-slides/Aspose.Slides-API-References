---
title: set_SlideShowType()
second_title: Aspose.Slides للـ C++ – مرجع API
description: "يضبط نوع عرض الشرائح. ممثل بواسطة الأسلاف التالية SlideShowType: BrowsedAtKiosk, PresentedBySpeaker و BrowsedByIndividual"
type: docs
weight: 14
url: /ar/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) طريقة

يضبط نوع عرض الشرائح. ممثل بواسطة الأسلاف التالية [SlideShowType](../../slideshowtype/): [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) و [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();

// لتعيين نوع "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// لتعيين نوع "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// لتعيين نوع "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [SlideShowType](../../slideshowtype/)
* فئة [SlideShowSettings](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)