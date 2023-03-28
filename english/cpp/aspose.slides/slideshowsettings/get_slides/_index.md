---
title: get_Slides()
second_title: Aspose.Slides for C++ API Reference
description: Slides range
type: docs
weight: 118
url: /cpp/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const method


[Slides](../../) range

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SlidesRange](../../slidesrange/)
* Class [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
