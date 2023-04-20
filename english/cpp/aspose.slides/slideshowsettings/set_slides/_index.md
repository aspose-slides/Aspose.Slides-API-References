---
title: set_Slides()
second_title: Aspose.Slides for C++ API Reference
description: Slides range
type: docs
weight: 131
url: /cpp/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) method


[Slides](../../) range

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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