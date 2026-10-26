---
title: get_Slides()
second_title: Aspose.Slides for C++ API hivatkozás
description: Diák tartománya
type: docs
weight: 118
url: /hu/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metódus


[Slides](../../) tartomány

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [SlidesRange](../../slidesrange/)
* Osztály [SlideShowSettings](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)