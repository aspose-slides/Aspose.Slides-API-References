---
title: get_SlideShowType()
second_title: Aspose.Slides برای C++ مرجع API
description: "نوع نمایش اسلاید را دریافت می‌کند. توسط اجداد SlideShowType زیر نشان داده می‌شود: BrowsedAtKiosk، PresentedBySpeaker و BrowsedByIndividual"
type: docs
weight: 1
url: /fa/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() متد


نوع نمایش اسلاید را دریافت می‌کند. توسط اجداد [SlideShowType](../../slideshowtype/) زیر نشان داده می‌شود: [BrowsedAtKiosk](../../browsedatkiosk/)، [PresentedBySpeaker](../../presentedbyspeaker/) و [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();

// برای تنظیم نوع "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// برای تنظیم نوع "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// برای تنظیم نوع "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [SlideShowType](../../slideshowtype/)
* کلاس [SlideShowSettings](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)