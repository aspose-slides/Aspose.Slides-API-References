---
title: get_SlideShowType()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحصل على نوع عرض الشرائح. ممثل بالأسلاف التالية من نوع SlideShowType: BrowsedAtKiosk، PresentedBySpeaker و BrowsedByIndividual"
type: docs
weight: 1
url: /ar/aspose.slides/slideshowsettings/get_slideshowtype/
---
## طريقة SlideShowSettings::get_SlideShowType()

يحصل على نوع عرض الشرائح. ممثلة بالأسلاف التالية [SlideShowType](../../slideshowtype/): [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) و [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();

// لتعيين النوع "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// لتعيين النوع "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// لتعيين النوع "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [SlideShowType](../../slideshowtype/)
* فئة [SlideShowSettings](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)