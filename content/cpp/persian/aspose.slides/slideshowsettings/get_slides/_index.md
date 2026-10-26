---
title: get_Slides()
second_title: Aspose.Slides برای C++ مرجع API
description: بازه اسلایدها
type: docs
weight: 118
url: /fa/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const متد

[Slides](../../) بازه

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [SlidesRange](../../slidesrange/)
* کلاس [SlideShowSettings](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)