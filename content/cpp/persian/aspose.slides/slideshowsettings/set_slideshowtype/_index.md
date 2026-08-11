---
title: set_SlideShowType()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع نمایش اسلاید را تنظیم می‌کند. نمایانده شده توسط اجداد SlideShowType زیر: BrowsedAtKiosk, PresentedBySpeaker و BrowsedByIndividual"
type: docs
weight: 14
url: /fa/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) متد


نوع نمایش اسلاید را تنظیم می‌کند. نمایانده شده توسط [SlideShowType](../../slideshowtype/) اجداد زیر: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) و [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>();

// تنظیم نوع "Browsed at a kiosk (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// تنظیم نوع "Browsed by individual (window)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// تنظیم نوع "Presented by a speaker (full screen)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [SlideShowType](../../slideshowtype/)
* کلاس [SlideShowSettings](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)